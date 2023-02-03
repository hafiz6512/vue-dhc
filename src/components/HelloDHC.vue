<template>
    <div class="welcome-msg">

        <h1>{{ msg }}</h1>

    </div>

    <div class="bootstrap-example">
        <h3>Bootstrap Test</h3>
        <br>
        <div class="btn-group">
           <button type="button" class="btn btn-success">Success</button>
           <button type="button" class="btn btn-danger mx-2">Danger</button>
           <button type="button" class="btn btn-warning">Warning</button>
        </div>

        <div class="bs-popover">
            <div class="py-2">
                <bs-popover
                    title="Hello Popover"
                    content="This is my content for the popover!"
                    trigger="hover">
                    <button class="btn btn-danger">Hover for popover</button>
                </bs-popover>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HelloDHC',
        props: {
            msg: String
        }
    }
</script>

