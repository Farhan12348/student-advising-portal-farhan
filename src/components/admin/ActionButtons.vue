<template>
  <q-td :props="props" class="text-right">
    <q-btn color="green" class="q-mx-sm">Approve</q-btn>
    <q-btn
      color="red"
      class="q-mx-sm"
      @click="TheDialogs.emit({ type: 'applicationRejectDialog', arg: {} })"
      >Reject</q-btn
    >
  </q-td>
</template>

<script setup>
import { TheDialogs } from 'src/dialogs/the-dialogs';

defineProps({
  props: Object,
});
</script>
