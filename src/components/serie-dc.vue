<templete>

 <div class="card-serie">
            <img :src="details.thumb" :alt="details.series">
            <h4>{{details.series}}</h4>
    </div>

</templete>

<script>
export default {
  name: 'SerieDc',
  props:{
      details:Object
  }

}
</script>

 <style scoped lang="scss">
 
 
 
 </style>
