 <template>
   <b-container class="testimonies">
        <b-row>
            <h2>Our testimonies</h2><br><br><br><br>
            <b-col class="test1">
                <b-img :src="require('../assets/img/test1.jpg')" width="200"></b-img>
                <h4>Ayantunde Peter</h4>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sit ea asperiores eaque illo perferendis laborum aperiam nobis odit corrupti similique ipsam ut, tenetur aspernatur veritatis vero. Quidem, incidunt? Itaque, quisquam.</p>
            </b-col>
            <b-col class="test2">
                <b-img :src="require('../assets/img/test2.jpg')" width="200"></b-img>
                <h4>adebanjo RAfat</h4>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sit ea asperiores eaque illo perferendis laborum aperiam nobis odit corrupti similique ipsam ut, tenetur aspernatur veritatis vero. Quidem, incidunt? Itaque, quisquam.</p>   
            </b-col>
            <b-col class="test2">
                <img src="" alt="img">
                <h4>Ade Nike</h4>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sit ea asperiores eaque illo perferendis laborum aperiam nobis odit corrupti similique ipsam ut, tenetur aspernatur veritatis vero. Quidem, incidunt? Itaque, quisquam.</p> 
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
    name: 'testimonies',
    data(){
       return {
          
       }
       
    }
}

</script>