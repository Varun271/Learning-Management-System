
// The following idea is taken from : https://www.youtube.com/watch?v=lcYn0tgUvHE&t=1619s
<template>
    <div class="container" style="margin-bottom: 30px">
        <form @submit.prevent="createMessage">
            <div class="form-group">
                <input type="text" name="message" class="form-control" placeholder="Enter message ..." v-model="newMessage">
                <p class="text-danger" v-if="errorText">{{ errorText }}</p>
            </div>
            <button class="btn btn-primary" type="submit" name="action">Submit</button>
        </form>
    </div>
</template>

<script src="createmessage.js">

</script>

