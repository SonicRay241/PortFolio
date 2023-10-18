<script lang="ts">
    import { onMount } from "svelte";
    
    onMount(()=>{
        const observer = new IntersectionObserver((entries)=>{
            entries.forEach((entry) => {
                if (entry.isIntersecting) {
                    entry.target.classList.add("show")
                }
            })
        })

        const hiddenElements = document.querySelectorAll(".hidden")
        hiddenElements.forEach((el) => observer.observe(el))
    })
</script>

<main>
    {#each [...Array(100).keys()] as i}
        <h1 class="testingg hidden">{i}</h1>
    {/each}
</main>