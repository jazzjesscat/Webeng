<template>
    <div>
        <form class="contact">
        Name:
            <input type="text" 
                   name="nn" 
                   size="30" 
                   maxlength="40">
        Vorname:
            <input type="text" 
                   name="nn" 
                   size="30" 
                   maxlength="40"> <br>
        E-mail:
            <input type="text" 
                   name="nn" 
                   size="30" 
                   maxlength="40"> <br>
        Betreff:
            <input type="text" 
                   name="nn" 
                   size="30" 
                   maxlength="40"> <br>
    
        Inhalt: 
           <textarea name="txt" rows="15" cols="50" maxlength="1000">
            Hier eure Narchicht ...
            </textarea>

        </form>
        
        
        
        
    </div>
</template>


<script>
export default {
    methods: {
        greet: function (event) {
            alert('Anfrage gesendet.')
        },
    },

}
</script>
