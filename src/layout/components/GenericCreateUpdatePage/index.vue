<template>
  <Page>
    <IBox>
      <GenericCreateUpdateForm ref="createUpdateForm" v-bind="$attrs" v-on="$listeners" />
    </IBox>
  </Page>
</template>
<script>
import IBox from '@/components/IBox'
import Page from '@/layout/components/Page'
import GenericCreateUpdateForm from '../GenericCreateUpdateForm'
export default {
  name: 'GenericCreateUpdatePage',
  components: {
    Page, IBox, GenericCreateUpdateForm
  }
}
</script>

<style scoped>
</style>
