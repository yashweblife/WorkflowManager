<template>
    <header>
        <h1>Workflow Manager</h1>
        <nav>
            <NuxtLink to="/settings">
                Settings
            </NuxtLink>
            <NuxtLink to="/projects">
                Projects
            </NuxtLink>
        </nav>
    </header>
</template>
	
<script>
export default {
    name:"HeaderComponent",
    data(){
        return{
            
        }
    },
}
</script>
	
<style scoped>
	
</style>