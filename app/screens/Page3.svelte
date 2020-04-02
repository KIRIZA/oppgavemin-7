<flexboxLayout class='flex-centered'>
    <label class='h1 text-center' text='page 3' />
        <cardView margin='32' elevation='40'>
            <button text='page 2' on:tap = { () => selectedTab = 0 } />
        </cardView>
</flexboxLayout>

<script>
    import Chart from './Chart.svelte';

    let data = [1,2,3,4,5,6]
</script>

<input type="number" bind:value={data[0]}>
<input type="number" bind:value={data[1]}>
<input type="number" bind:value={data[2]}>
<input type="number" bind:value={data[3]}>
<input type="number" bind:value={data[4]}>
<input type="number" bind:value={data[5]}>

<Chart {data} />

