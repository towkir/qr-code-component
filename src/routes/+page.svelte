<script>
    import QRCode from "./QRCode.svelte";
</script>
<div class="component-wrapper">
    <QRCode />
</div>

<svelte:head>
    <title>QR Code Component</title>
</svelte:head>

<style>
    .component-wrapper {
        min-height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>
