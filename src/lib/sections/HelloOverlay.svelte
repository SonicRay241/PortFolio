<script lang="ts">
    import { onMount } from "svelte";

    let textH: SVGPathElement, textE: SVGPathElement, textL: SVGPathElement, textL2: SVGPathElement, textO: SVGPathElement, textDot: SVGPathElement;
    let overlay: HTMLDivElement
    let stroke = "transparent"
    onMount(() => {
        stroke = "white"
        textH.style.strokeDasharray = textH.getTotalLength().toString();
        textH.style.strokeDashoffset = textH.getTotalLength().toString();
        textE.style.strokeDasharray = textH.getTotalLength().toString();
        textE.style.strokeDashoffset = textH.getTotalLength().toString();
        textL.style.strokeDasharray = textH.getTotalLength().toString();
        textL.style.strokeDashoffset = textH.getTotalLength().toString();
        textL2.style.strokeDasharray = textH.getTotalLength().toString();
        textL2.style.strokeDashoffset = textH.getTotalLength().toString();
        textO.style.strokeDasharray = textH.getTotalLength().toString();
        textO.style.strokeDashoffset = textH.getTotalLength().toString();
        textDot.style.strokeDasharray = textH.getTotalLength().toString();
        textDot.style.strokeDashoffset = textH.getTotalLength().toString();

        setTimeout(()=>{
            overlay.style.display = "none";
        }, 4100)
    })
</script>

<div class="main" bind:this={overlay}>
    <svg width="340" height="96" viewBox="0 0 340 96" fill="none" xmlns="http://www.w3.org/2000/svg" id="hello-text">
        <path 
            d="M2.08521 91V92.5H3.58521H22.0369H23.5369V91V56.4489H57.9943V91V92.5H59.4943H77.9034H79.4034V91V3.72726V2.22726H77.9034H59.4943H57.9943V3.72726V38.2358H23.5369V3.72726V2.22726H22.0369H3.58521H2.08521V3.72726V91Z" 
            stroke="{stroke}" 
            stroke-width="3" 
            bind:this={textH}
        />
        <path 
            d="M106.875 89.4904L106.884 89.4955C112.009 92.3724 118.068 93.7784 125.005 93.7784C130.553 93.7784 135.507 92.9317 139.838 91.1995L139.843 91.1975C144.18 89.4448 147.764 86.9876 150.551 83.8067C153.367 80.5962 155.228 76.838 156.132 72.5601L156.489 70.8672L154.763 70.7532L137.973 69.6453L136.866 69.5722L136.472 70.6101C135.921 72.0627 135.132 73.2611 134.113 74.232C133.089 75.2071 131.847 75.9509 130.362 76.4544C128.861 76.9632 127.179 77.2273 125.303 77.2273C122.477 77.2273 120.118 76.6345 118.169 75.5104C116.214 74.382 114.694 72.7819 113.599 70.6714C112.709 68.9108 112.171 66.8358 112.019 64.4176H155.048H156.548V62.9176V57.9318C156.548 52.2281 155.748 47.1842 154.108 42.8307C152.48 38.4782 150.181 34.8193 147.194 31.8915C144.255 28.9834 140.805 26.8097 136.859 25.3739C132.958 23.9153 128.76 23.1932 124.281 23.1932C117.633 23.1932 111.763 24.6662 106.724 27.6656L106.72 27.6676C101.727 30.6575 97.8569 34.8326 95.1199 40.1581C92.3794 45.49 91.0335 51.6418 91.0335 58.571C91.0335 65.6637 92.3767 71.8897 95.1214 77.2001L95.123 77.2031C97.867 82.4823 101.79 86.5888 106.875 89.4904ZM136.388 50.1676H112.149C112.391 48.6551 112.88 47.2605 113.611 45.9734L113.611 45.9734L113.615 45.9659C114.679 44.0654 116.14 42.5668 118.016 41.4512L118.021 41.4482C119.894 40.3245 122.065 39.7443 124.579 39.7443C126.994 39.7443 129.04 40.2744 130.767 41.2858L130.778 41.2922L130.789 41.2983C132.567 42.3002 133.946 43.6796 134.948 45.4578C135.728 46.8418 136.214 48.4049 136.388 50.1676Z" 
            stroke="{stroke}" 
            stroke-width="3"
            bind:this={textE}
        />
        <path 
            d="M188.948 3.72726V2.22726H187.448H169.294H167.794V3.72726V91V92.5H169.294H187.448H188.948V91V3.72726Z" 
            stroke="{stroke}" 
            stroke-width="3"
            bind:this={textL}
        />
        <path 
            d="M224.043 3.72726V2.22726H222.543H204.39H202.89V3.72726V91V92.5H204.39H222.543H224.043V91V3.72726Z" 
            stroke="{stroke}" 
            stroke-width="3"
            bind:this={textL2}
        />
        <path 
            d="M269.059 92.2784C262.439 92.2784 256.715 90.8722 251.885 88.0597C247.084 85.2187 243.377 81.2699 240.763 76.2131C238.15 71.1278 236.843 65.2329 236.843 58.5284C236.843 51.767 238.15 45.8579 240.763 40.8011C243.377 35.7159 247.084 31.767 251.885 28.9545C256.715 26.1136 262.439 24.6932 269.059 24.6932C275.678 24.6932 281.388 26.1136 286.189 28.9545C291.019 31.767 294.741 35.7159 297.354 40.8011C299.968 45.8579 301.275 51.767 301.275 58.5284C301.275 65.2329 299.968 71.1278 297.354 76.2131C294.741 81.2699 291.019 85.2187 286.189 88.0597C281.388 90.8722 275.678 92.2784 269.059 92.2784ZM269.144 78.2159C272.155 78.2159 274.67 77.3636 276.687 75.6591C278.704 73.9261 280.224 71.5682 281.246 68.5852C282.297 65.6023 282.823 62.2074 282.823 58.4006C282.823 54.5937 282.297 51.1989 281.246 48.2159C280.224 45.2329 278.704 42.875 276.687 41.142C274.67 39.4091 272.155 38.5426 269.144 38.5426C266.104 38.5426 263.547 39.4091 261.474 41.142C259.428 42.875 257.88 45.2329 256.829 48.2159C255.806 51.1989 255.295 54.5937 255.295 58.4006C255.295 62.2074 255.806 65.6023 256.829 68.5852C257.88 71.5682 259.428 73.9261 261.474 75.6591C263.547 77.3636 266.104 78.2159 269.144 78.2159Z" 
            stroke="{stroke}" 
            stroke-width="3"
            bind:this={textO}
        />
        <path 
            d="M317.777 90.1781L317.784 90.1857L317.792 90.1932C320.088 92.4563 322.88 93.608 326.089 93.608C328.195 93.608 330.151 93.0861 331.925 92.0348L331.934 92.0296L331.943 92.0243C333.679 90.9633 335.084 89.558 336.146 87.8224C337.26 86.0187 337.817 84.027 337.817 81.8807C337.817 78.6803 336.622 75.9093 334.294 73.6461C331.983 71.3992 329.227 70.2386 326.089 70.2386C322.88 70.2386 320.088 71.3903 317.792 73.6534L317.792 73.6534L317.784 73.6609C315.518 75.9277 314.362 78.6943 314.362 81.8807C314.362 85.0905 315.514 87.8827 317.777 90.1781Z" 
            stroke="{stroke}" 
            stroke-width="3"
            bind:this={textDot}
        />
        </svg>        
</div>

<style>
    .main {
        height: 97vh;
        width: 100%;
        position: fixed;
        animation: gone 0.3s ease forwards 4000ms;
        background-color: var(--background);
    }

    .main svg {
        position: relative;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    #hello-text {
        animation: filltext 0.3s ease forwards 2000ms;
    }

    /* h */
    #hello-text path:nth-child(1){
        animation: line-anim 2s ease forwards;
    }
    /* e */
    #hello-text path:nth-child(2){
        animation: line-anim 2s ease forwards 200ms; 
    }
    /* l */
    #hello-text path:nth-child(3){
        animation: line-anim 2s ease forwards 400ms;
    }
    /* l */
    #hello-text path:nth-child(4){
        animation: line-anim 2s ease forwards 600ms;
    }
    /* o */
    #hello-text path:nth-child(5){
        animation: line-anim 2s ease forwards 800ms;
    }
    /* . */
    #hello-text path:nth-child(6){
        animation: line-anim 2s ease forwards 1000ms;
    }

    @keyframes line-anim {
        to {
            stroke-dashoffset: 0;
        }
    }

    @keyframes filltext {
        from {
            fill: transparent;
        }
        to {
            fill: white;
        }
    }
    
    @keyframes gone {
        from {
            opacity: 1;
        }
        to {
            opacity: 0;
            transform: scale(200%);
        }
    }
</style>