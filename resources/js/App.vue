<template>
    <div className="container">
        <nav className="navbar navbar-expand-lg navbar-light bg-light">
            <div className="collapse navbar-collapse">
                <div className="navbar-nav">
                    <router-link to="/" className="nav-item nav-link">Products List</router-link>
                    <router-link to="/create" className="nav-item nav-link">Create Product</router-link>
                </div>
            </div>
        </nav>
        <router-view></router-view>
    </div>
</template>

<script>
    export default {}
</script>
