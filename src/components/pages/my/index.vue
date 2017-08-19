<style>

</style>
<template>
  <div class="my">
      my
  </div>
</template>
<script>
import { test1, test2 } from 'api/list1'
export default {
    data () {
        return {

        }
    },
    created () {
        this._test3()
    },
    mounted () {

    },
    methods: {
        _test3 () {
            test1('my')
        }
    }
}
</script>
