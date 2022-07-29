<script>
 
      let time ='';
      
        setInterval(() => {
           let  a = new Date(); 
           let date = a.toLocaleDateString(undefined);
           time = a.getHours() + ':' + a.getMinutes() + ':' + a.getSeconds();
            
        }, 1000);
    

</script>
<div class="clocky" style="margin-top: 180px;text-align:center;">
<center>   <div id="MyClockDisplay" class="clock" >{time}</div></center> 
</div>

<style>
    .clock{
        width: 50%;
        border: 3px rgb(9, 218, 250) solid;
        font-size:8em;
        font-weight: 600;
    }
</style>