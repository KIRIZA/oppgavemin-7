<page class='bg-primary'>
    <actionBar title='My world'/>
    <cardView elevation='40' margin='50' >
    <flexboxLayout class='flex-centered'>
        <label class='h2' text='Dette er mine sider' />
        <button text='back' on:tap={goBack} />
    </flexboxLayout>
    </cardView>
</page>

<script>
    import { goBack } from 'svelte-native'
</script>