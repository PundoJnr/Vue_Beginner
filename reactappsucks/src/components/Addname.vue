<template>
<div class="add-name">
<input type="text" v-model="userName">
<h2>My name is {{userName}}</h2>
</div>
</template>

<script>
import{mapState} from 'vuex';

export default {
    name: 'userName',
    data(){
        return {
            userName: "Arthur Sidney",
    };
    },

    
}
</script>
                                                                                                                                                                                                                