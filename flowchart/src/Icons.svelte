<svg class="icon-wrapper" width={width} height={height}>
    <symbol id="ellipse-i" viewBox="0 0 1024 1024">
        <path d="M512 998.4C243.776 998.4 25.6 780.224 25.6 512S243.776 25.6 512 25.6s486.4 218.176 486.4 486.4-218.176 486.4-486.4 486.4zM512 76.8C272 76.8 76.8 272 76.8 512s195.2 435.2 435.2 435.2 435.2-195.2 435.2-435.2S752 76.8 512 76.8z"/>
    </symbol>
    <symbol id="square-i" viewBox="0 0 1024 1024">
        <path d="M832 928H192c-52.928 0-96-43.072-96-96V192c0-52.928 43.072-96 96-96h640c52.928 0 96 43.072 96 96v640c0 52.928-43.072 96-96 96zM192 160c-17.632 0-32 14.368-32 32v640c0 17.664 14.368 32 32 32h640c17.664 0 32-14.336 32-32V192c0-17.632-14.336-32-32-32H192z"/>
    </symbol>
    <symbol id="rhombus-i" viewBox="0 0 1024 1024">
        <path d="M511.9233084 148.91700253l363.00630586 363.00630587-363.00630586 363.00630586-363.00630587-363.00630586 363.00630586-363.00630586m1e-8-86.91700254l-449.9233084 449.92330839 449.9233084 449.92330841 449.9233084-449.92330841-449.92330841-449.92330839z"/>
    </symbol>
    <g>
        <title>{id}</title>
        <use xlink:href={symId} x="0" y="0"  width={width} height={height} fill="#2f54cd" />
    </g>
</svg>
<script>
    export let width = 40
    export let height = 40
    export let id = 'square'
    $: symId = `#${id}-i`
</script>
<style>
.icon-wrapper{
  margin: 5px 0;
}
</style>
