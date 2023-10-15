<script lang="ts">
    import { onMount } from "svelte";
    let hello: HTMLHeadElement, name: HTMLHeadElement, profession: HTMLHeadElement, about: HTMLParagraphElement;
    let role: string = "Web Developer"
    let transformRole = "transform: scale(1);"
    const currentRole = "University Student"
    onMount(()=>{
        // hello.style.color = "#00e5ff"
        // setTimeout(()=>{
        //     name.style.color = "#fff"
        // }, 300)
        // setTimeout(()=>{
        //     profession.style.color = "#cfcfcf"
        // }, 600)
        // setTimeout(()=>{
        //     about.style.color = "#fff"
        // }, 900)

        setTimeout(()=>{
            transformRole = "transform: scale(0.6);"
            setTimeout(()=>{
                role = "iOS Developer"
                transformRole = "transform: scale(1);"
            }, 300)
        }, 5900)
        setTimeout(()=>{
            transformRole = "transform: scale(0.6);"
            setTimeout(()=>{
                role = currentRole
                transformRole = "transform: scale(1);"
            }, 300)
        }, 6900)


        // setTimeout(()=>{
        //     role = "University Student"
        // }, 7900)

        // setTimeout(()=>{
        //     role = ""
        //     fill = "I make things"
        // }, 8900)
    })
</script>

<div class="main">
    <!-- <p class="section-name">01. INTRO</p> -->
    <div class="intro-container">
        <div class="text-side">
            <h3 class="text blue intro-text" style="opacity:0;transform: translateY(50px);" bind:this={hello}>Hello, i'm</h3>
            <h1 class="title intro-text" style="opacity:0;transform: translateY(50px);" bind:this={name}>Rayhan Permana</h1>
            <h2 class="subtitle off-white intro-text" style="opacity:0;transform: translateY(50px);" bind:this={profession}>I'm a <span style="{transformRole} transition: transform 0.3s ease">{role}</span>.</h2>
            <!-- I'm currently working in Binus IT Division as a Web Developer Associate. -->
            <p class="text intro-text" style="opacity:0;transform: translateY(50px);" bind:this={about}>I'm currently a student at Binus University, where i took a major at Data Science so i can learn how to create neural networks.</p>
        </div>
        <div class="image-side">
            
        </div>
    </div>
</div>

<style>
    .main {
        height: 98vh;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .intro-container {
        height: 60vh;
        width: 60vw;
        display: grid;
        grid-template-columns: 11fr 9fr;
        grid-template-rows: 1fr;
        column-gap: 0px;
        row-gap: 0px;
    }

    .text-side :nth-child(1) {
        animation: display-text 1s ease forwards 4500ms;
    }
    .text-side :nth-child(2) {
        animation: display-text 1s ease forwards 4700ms;
    }
    .text-side :nth-child(3) {
        animation: display-text 1s ease forwards 4900ms;
    }
    .text-side :nth-child(4) {
        animation: display-text 1s ease forwards 5100ms;
    }

    @keyframes display-text{
        to {
            opacity: 1;
            transform: translateY(0px);
        }
    }

    /* .image-side {
        
    } */

    @media screen and (max-width: 1000px) {
        .intro-container {
            width: 90vw;
        }
    }

    @media screen and (max-width: 1500px) {
        .intro-container {
            width: 80vw;
        }
    }

    @media screen and (max-width: 1100px) {
        .image-side {
            display: none;
        }
        .intro-container {
            grid-template-columns: 1fr;
        }
    }
</style>