<script lang="ts">
    import { onMount } from "svelte";

    let overlay: HTMLDivElement

    let path1: SVGPathElement
    let path2: SVGPathElement
    let path3: SVGPathElement
    let path4: SVGPathElement
    let path5: SVGPathElement
    let path6: SVGPathElement
    let path7: SVGPathElement
    let path8: SVGPathElement
    let path9: SVGPathElement
    let path10: SVGPathElement
    let path11: SVGPathElement


    onMount(()=>{
        path1.style.strokeDasharray = path1.getTotalLength().toString();
        path1.style.strokeDashoffset = path1.getTotalLength().toString();
        path2.style.strokeDasharray = path2.getTotalLength().toString();
        path2.style.strokeDashoffset = path2.getTotalLength().toString();
        path3.style.strokeDasharray = path3.getTotalLength().toString();
        path3.style.strokeDashoffset = path3.getTotalLength().toString();
        path4.style.strokeDasharray = path4.getTotalLength().toString();
        path4.style.strokeDashoffset = path4.getTotalLength().toString();
        path5.style.strokeDasharray = path5.getTotalLength().toString();
        path5.style.strokeDashoffset = path5.getTotalLength().toString();
        path6.style.strokeDasharray = path6.getTotalLength().toString();
        path6.style.strokeDashoffset = path6.getTotalLength().toString();
        path7.style.strokeDasharray = path7.getTotalLength().toString();
        path7.style.strokeDashoffset = path7.getTotalLength().toString();
        path8.style.strokeDasharray = path8.getTotalLength().toString();
        path8.style.strokeDashoffset = path8.getTotalLength().toString();
        path9.style.strokeDasharray = path9.getTotalLength().toString();
        path9.style.strokeDashoffset = path9.getTotalLength().toString();
        path10.style.strokeDasharray = path10.getTotalLength().toString();
        path10.style.strokeDashoffset = path10.getTotalLength().toString();
        path11.style.strokeDasharray = path11.getTotalLength().toString();
        path11.style.strokeDashoffset = path11.getTotalLength().toString();
    })
    // setTimeout(()=>{
    //     overlay.style.display = "none";
    // }, 4100)
</script>


<div class="main" bind:this={overlay}>
    <svg width="292" height="96" viewBox="0 0 2915 962" fill="none" xmlns="http://www.w3.org/2000/svg" id="hello-text">
        <path d="M44.1562 869.828C118.669 826.162 282.358 723.687 341.007 663.115" stroke="url(#paint0_linear_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path1}/>
        <path d="M441.959 542.932C491.234 490.453 593.819 362.085 615.022 172.771C631.847 22.5432 480.315 -3.1098 431.143 129.505C391.483 236.468 372.254 573.379 349.419 734.022" stroke="url(#paint1_angular_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path2}/>
        <path d="M312.163 914.296C326.184 820.954 365.043 633.07 429.942 556.153C501.26 471.627 640.211 450.938 657.086 591.005C669.105 690.757 601.802 839.782 667.903 890.259C734.003 940.735 899.855 897.47 969.56 850.599" stroke="url(#paint2_linear_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path3}/>
        <path d="M980.377 840.677C1048.88 808.227 1143.98 736.957 1175.07 627.592C1215.18 486.531 1059.56 425.182 969.561 528.511C901.056 607.161 887.837 770.824 983.983 843.483" stroke="url(#paint3_angular_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path4}/>
        <path d="M958.743 819.352C1022.44 904.681 1238.29 979.675 1428.66 779.692" stroke="url(#paint4_linear_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path5}/>
        <path d="M1462.31 743.637C1515.99 675.934 1631.76 519.377 1670.22 381.888C1718.3 210.028 1727.91 88.6436 1663.01 57.396C1590.9 22.6764 1501.97 119.22 1462.31 317.521C1434.37 457.21 1428.66 530.914 1428.66 636.675" stroke="url(#paint5_angular_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path6}/>
        <path d="M1428.66 641.482C1426.65 730.417 1452.69 914.055 1606.53 917.901C1785.6 922.378 1911.39 755.655 1967.07 672.729" stroke="url(#paint6_linear_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path7}/>
        <path d="M1970.68 666.721C2018.75 592.207 2100.86 427.971 2135.33 290.55C2174.99 132.441 2153.85 77.3248 2099.27 58.5982C2030.77 35.0928 1953.85 128.304 1916.6 290.55C1882.59 438.649 1846.89 634.271 1890.16 759.261" stroke="url(#paint7_angular_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path8}/>
        <path d="M1874.53 687.682C1882.94 788.635 1960.91 912.652 2058.41 916.699C2187.01 922.038 2278.34 824.159 2337.23 642.684" stroke="url(#paint8_linear_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path9}/>
        <path d="M2338.44 642.684C2308.39 771.279 2336.51 922.228 2487.46 915.498C2638.41 908.767 2679.35 758.86 2680.95 684.747C2687.76 613.84 2663.17 478.034 2519.91 478.034" stroke="url(#paint9_angular_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path10}/>
        <path d="M2340.84 629.464C2355.26 578.987 2409.58 478.034 2511.5 478.034C2638.89 478.034 2629.28 539.327 2720.62 536.923C2793.69 535 2851.21 484.844 2870.84 460.007" stroke="url(#paint10_linear_1_803)" stroke-width="86.5313" stroke-linecap="round" bind:this={path11}/>
        <defs>
        <linearGradient id="paint0_linear_1_803" x1="341.006" y1="664.317" x2="-29.155" y2="923.91" gradientUnits="userSpaceOnUse">
        <stop stop-color="#157B93"/>
        <stop offset="1" stop-color="#037A92"/>
        </linearGradient>
        <radialGradient id="paint1_angular_1_803" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(455.179 416.07) rotate(97.5087) scale(588.602 532.006)">
        <stop offset="0.0115615" stop-color="#ACD15E"/>
        <stop offset="0.735556" stop-color="#29949C"/>
        <stop offset="0.881674" stop-color="#23929E"/>
        <stop offset="0.955023" stop-color="#1E91A0"/>
        </radialGradient>
        <linearGradient id="paint2_linear_1_803" x1="312.163" y1="885.452" x2="927.496" y2="914.296" gradientUnits="userSpaceOnUse">
        <stop stop-color="#D6D90D"/>
        <stop offset="0.494792" stop-color="#FAD500"/>
        <stop offset="1" stop-color="#FDD35D"/>
        </linearGradient>
        <radialGradient id="paint3_angular_1_803" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(988.79 779.692) rotate(125.383) scale(361.149 323.508)">
        <stop offset="0.149479" stop-color="#FF9932"/>
        <stop offset="0.735351" stop-color="#FFD570"/>
        </radialGradient>
        <linearGradient id="paint4_linear_1_803" x1="1401.01" y1="779.691" x2="994.797" y2="849.397" gradientUnits="userSpaceOnUse">
        <stop stop-color="#FF9246"/>
        <stop offset="1" stop-color="#FF9F38"/>
        </linearGradient>
        <radialGradient id="paint5_angular_1_803" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(1569.27 278.531) rotate(108.021) scale(578.831 203.659)">
        <stop offset="0.0268639" stop-color="#F45343"/>
        <stop offset="0.908962" stop-color="#FD9156"/>
        </radialGradient>
        <linearGradient id="paint6_linear_1_803" x1="1447.89" y1="818.15" x2="1935.83" y2="919.103" gradientUnits="userSpaceOnUse">
        <stop stop-color="#F55544"/>
        <stop offset="1" stop-color="#EE7271"/>
        </linearGradient>
        <radialGradient id="paint7_angular_1_803" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(1997.12 386.696) rotate(103.182) scale(469.051 191.903)">
        <stop offset="0.00079382" stop-color="#EF716F"/>
        <stop offset="0.0273104" stop-color="#9174B5"/>
        </radialGradient>
        <linearGradient id="paint8_linear_1_803" x1="1912" y1="817.882" x2="2316.92" y2="887.075" gradientUnits="userSpaceOnUse">
        <stop stop-color="#9575B3"/>
        <stop offset="1" stop-color="#625EAA"/>
        </linearGradient>
        <radialGradient id="paint9_angular_1_803" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(2504.85 696.874) rotate(90) scale(218.84 177.122)">
        <stop offset="0.277174" stop-color="#6C9DE2"/>
        <stop offset="0.6442" stop-color="#6163B8"/>
        </radialGradient>
        <linearGradient id="paint10_linear_1_803" x1="2340.84" y1="610.234" x2="2897.28" y2="523.703" gradientUnits="userSpaceOnUse">
        <stop stop-color="#6C99DF"/>
        <stop offset="0.586308" stop-color="#51A5D3"/>
        <stop offset="1" stop-color="#7FB6DD"/>
        </linearGradient>
        </defs>
        </svg>
</div>

<style>
    .main {
        height: 100%;
        width: 100vw;
        position: fixed;
        animation: gone 0.3s ease forwards 3000ms;
        background-color: var(--background);
    }

    .main svg {
        position: relative;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    #hello-text path:nth-child(1){
        animation: line-anim 200ms ease-in forwards;
    }
    #hello-text path:nth-child(2){
        animation: line-anim 200ms linear forwards 200ms; 
    }
    #hello-text path:nth-child(3){
        animation: line-anim 200ms linear forwards 400ms;
    }
    #hello-text path:nth-child(4){
        animation: line-anim 200ms linear forwards 600ms;
    }
    #hello-text path:nth-child(5){
        animation: line-anim 200ms linear forwards 800ms;
    }
    #hello-text path:nth-child(6){
        animation: line-anim 200ms linear forwards 1000ms;
    }
    #hello-text path:nth-child(7){
        animation: line-anim 200ms linear forwards 1200ms;
    }
    #hello-text path:nth-child(8){
        animation: line-anim 200ms linear forwards 1400ms;
    }
    #hello-text path:nth-child(9){
        animation: line-anim 200ms linear forwards 1600ms;
    }
    #hello-text path:nth-child(10){
        animation: line-anim 200ms linear forwards 1800ms;
    }
    #hello-text path:nth-child(11){
        animation: line-anim 200ms ease-out forwards 2000ms;
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