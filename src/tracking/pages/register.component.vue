<script>
//
//import {ref} from "vue";
//import {
//  getAuth,
//  createUserWithEmailAndPassword,
//  GoogleAuthProvider,
//  signInWithPopup,
//} from "firebase/auth";
//import { useRouter } from 'vue-router'
//const email = ref("");
//const password = ref("");
//const router = useRouter();
//const register = () => {
//  createUserWithEmailAndPassword(getAuth(), email.value, password.value)
//      .then((data) => {
//        console.log("Successfully registered!");
//        router.push('/feed');
//      })
//      .catch((error) => {
//        console.log(error);
//        alert(error.message);
//      });
//};
//
//const signInWithGoogle = () => {
//  const provider = new GoogleAuthProvider();
//  signInWithPopup(getAuth(),provider)
//      .then((result) => {
//        console.log(result.user);
//        router.push('/feed');
//      })
//      .catch((error) => {
//
//      })
//}
//
//export default {
//  name: "register.component"
//}
</script>

<template>
  <h1>Create an account</h1>
  <p><input type="text" placeholder="Email" v-model="email"/></p>
  <p><input type="text" placeholder="Password" v-model="password"/></p>
  <p><button @click="register">Submit</button></p>
  <p><button @click="signInWithGoogle">Sign In With Google</button></p>
</template>

<style scoped>

</style>