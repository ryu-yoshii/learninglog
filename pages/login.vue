<template>
<v-app>
    <v-card>
        <v-card-title>
            <h1 class="display-1">ログイン</h1>
        </v-card-title>
        <v-card-text>
            <v-form>
                <v-text-field prepend-icon="mdi-account-circle" label="ユーザ名" />
                <v-text-field prepend-icon="mdi-account-lock" type="password" label="パスワード" />
            </v-form>
            <v-btn  elevation="2">
                ログイン
            </v-btn>
        </v-card-text>
    </v-card>
</v-app>
</template>

<script>

export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>