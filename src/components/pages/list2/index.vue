<style>

</style>
<template>
  <div class="list2">
      list2
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
        this._test2()
    },
    mounted () {

    },
    methods: {
        _test2 () {
            test1('list2')
        }
    }
}
</script>
