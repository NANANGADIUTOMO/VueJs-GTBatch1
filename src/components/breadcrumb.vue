<template>
<breadcrumb>
    <div class="breadcrumb">
        <nav class="navbar navbar-expand-lg mt-2 "  >
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown"  aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                    </button>
                        <div class="collapse navbar-collapse" id="navbarNavDropdown">
                            <ul class="navbar-nav">
                                <li class="nav-item active">
                                <a class="nav-link text-dark" href="#"><b>Home /</b><span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item active">
                                    <a class="nav-link text-dark" href="#"><b>Office Room /</b><span class="sr-only">(current)</span></a>
                                    </li>
                                <li class="nav-item active" type="option">
                                <a class="nav-link text-dark" href="#"><b>Details</b><span class="sr-only">(current)</span></a>
                                </li>
                            </ul>
                        </div>
                        
            </nav>
    </div>
</breadcrumb>
</template>

<script>
export default {
    name : 'breadcrumbComponent'
}
</script>

<style scoped>
.breadcrumb{
    margin-top: 5px;
    
}
</style>