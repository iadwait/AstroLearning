<script>
    let count = 0;
</script>

<button on:click={() => count++}>
    Count: {count}
</button>

<style>
    button {
        padding: 8px 16px;
        background-color: #4caf50;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        font-size: 16px;
    }
    button:hover {
        background-color: #45a049;
    }
</style>
