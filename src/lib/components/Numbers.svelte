<script>
  let { start = 0 } = $props();

  const step = 0.5; // 5s / 10 values
  const begin = -start * step;
</script>

<svg class="seven-segment" width="80" height="100"
     viewBox="0 0 22 36" preserveAspectRatio="xMidYMid">
  <g stroke="#000" fill="#000" stroke-width="0.2">
    <polygon class="A" points=" 5, 4  7, 6 15, 6 17, 4 15, 2  7, 2">
      <animate attributeName="opacity" begin="{begin}s" dur="5s" repeatCount="indefinite"
               calcMode="discrete" fill="freeze"
               values="1;0;1;1;0;1;1;1;1;1;"/>
    </polygon>
    <polygon class="B" points="18, 5 16, 7 16,15 18,17 20,15 20, 7">
      <animate attributeName="opacity" begin="{begin}s" dur="5s" repeatCount="indefinite"
               calcMode="discrete" fill="freeze"
               values="1;1;1;1;1;0;0;1;1;1;"/>
    </polygon>
    <polygon class="C" points="18,19 16,21 16,29 18,31 20,29 20,21">
      <animate attributeName="opacity" begin="{begin}s" dur="5s" repeatCount="indefinite"
               calcMode="discrete" fill="freeze"
               values="1;1;0;1;1;1;1;1;1;1;"/>
    </polygon>
    <polygon class="D" points=" 5,32  7,34 15,34 17,32 15,30  7,30">
      <animate attributeName="opacity" begin="{begin}s" dur="5s" repeatCount="indefinite"
               calcMode="discrete" fill="freeze"
               values="1;0;1;1;0;1;1;0;1;1;"/>
    </polygon>
    <polygon class="E" points=" 4,19  2,21  2,29  4,31  6,29  6,21">
      <animate attributeName="opacity" begin="{begin}s" dur="5s" repeatCount="indefinite"
               calcMode="discrete" fill="freeze"
               values="1;0;1;0;0;0;1;0;1;0;"/>
    </polygon>
    <polygon class="F" points=" 4, 5  2, 7  2,15  4,17  6,15  6, 7">
      <animate attributeName="opacity" begin="{begin}s" dur="5s" repeatCount="indefinite"
               calcMode="discrete" fill="freeze"
               values="1;0;0;0;1;1;1;0;1;1;"/>
    </polygon>
    <polygon class="G" points=" 5,18  7,20 15,20 17,18 15,16  7,16">
      <animate attributeName="opacity" begin="{begin}s" dur="5s" repeatCount="indefinite"
               calcMode="discrete" fill="freeze"
               values="0;0;1;1;1;1;1;0;1;1;"/>
    </polygon>
  </g>
</svg>
