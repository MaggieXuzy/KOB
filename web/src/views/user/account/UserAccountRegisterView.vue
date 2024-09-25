<template>
    <ContentField>
        <div class="row justify-content-md-center">
            <div class="col-3">
                <form>
                    <div class="mb-3">
                      <label for="username" class="form-label">Username</label>
                      <input type="text" class="form-control" id="username" placeholder="Please enter your username">
                    </div>
                    <div class="mb-3">
                        <label for="password" class="form-label">Password</label>
                        <input type="password" class="form-control" id="password" placeholder="Please enter your password">
                    </div>
                </form>
            </div>
        </div>
    </ContentField>
</template>

<script>
import ContentField from "../../../components/ContentField.vue"

export default {
    components: {
        ContentField,
    }
}
</script>

<style scoped>
</style>