<template>
    <div>
        Page A - <strong>{{</strong> message <strong>}}</strong>
    </div>
</template>
<script>
    export default {
        name: 'PageA',
        data() {
            return {
                message: 'Data from Page A'
            };
        }
    };
</script>