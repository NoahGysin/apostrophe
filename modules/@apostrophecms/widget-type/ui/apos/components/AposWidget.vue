<template>
  <!-- eslint-disable-next-line vue/no-v-html -->
  <div v-html="rendered" />
</template>

<script>
// This component renders a widget in the editor. It is not involved
// when the user does not have editing privileges.

import AposWidgetMixin from 'Modules/@apostrophecms/widget-type/mixins/AposWidgetMixin';

export default {
  name: 'AposWidget',
  mixins: [ AposWidgetMixin ]
};

</script>
