<script>
    import Header from '../components/Header.svelte';
    import Main from '../components/Main.svelte';
    import Sidebar from '../components/Sidebar.svelte'
    import TimeLine from '../components/Timeline.svelte'
</script>
<div class="main">
    <Header />
    <Main>
        <TimeLine />
        <Sidebar />
    </Main>
</div>

<style>
    :global(body){
        background-color: #676778;
        color: white;
    }
</style>