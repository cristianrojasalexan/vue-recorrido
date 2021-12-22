<template>
    <div id="dashboardIndex">
        <Navbar>
        </Navbar>
        <Sidebar>
        </Sidebar>
    </div>
</template>

<script>
    import Navbar from './partials/Navbar'
    import Sidebar from './partials/Sidebar'

    export default {
        name: 'dashboardIndex',
        components: { Navbar, Sidebar }
    }
</script>