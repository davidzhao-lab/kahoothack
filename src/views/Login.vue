<template>
  <div>
    <PageHeader title="Omegaboot Kahoot Bot" subtitle="Created by @idiidk, Updated to support V2!" />
    <LoginForm />
    <InfoBox class="infoBox" />
  </div>
</template>

<script>
import PageHeader from "@/components/PageHeader";
import LoginForm from "@/components/LoginForm";
import InfoBox from "@/components/InfoBox";

export default {
  components: {
    PageHeader,
    LoginForm,
    InfoBox
  }
};
</script>

<style scoped>
.infoBox {
  margin-top: 5vh;
}
</style>
