<template>
    <main>
    </main>
</template>

<script>
export default {
    
}
</script>

<style lang="sass">
main
    display: flex
    justify-content: center
    align-items: center
    height: 100%
    .wrapper
        width: 100%
        height: 100%
        display: flex
        .upload
            border-right: 2px dashed #efefef
            padding: 0 1em
            display: flex
            flex: 1
            flex-direction: column
            justify-content: flex-start
            height: 100%
            .input-dialog
                display: none
            .file-btn
                background: #0096ff
                color: #fff
                border: none
                padding: 1em 3em
                border-radius: 2em
                // &:before // use later
                //     content: '\f574'
        .content
            display: flex
            flex: 3
</style>
