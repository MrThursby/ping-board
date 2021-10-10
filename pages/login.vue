<template>
  <div>
    <b-form-group
      label="Логин"
    >
      <b-form-input v-model="form.login" />
    </b-form-group>
    <b-form-group
      label="Пароль"
    >
      <b-form-input v-model="form.password" />
    </b-form-group>
  </div>
</template>

<script>
export default {
  name: "login",
  layout: "sign",
  data: () => ({
    form: {
      login: '',
      password: '',
    }
  })
}
</script>
