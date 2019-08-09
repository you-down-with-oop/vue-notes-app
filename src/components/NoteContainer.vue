<template>
  <div class="note-container">
    <note-selectors />
    <note-editor />
  </div>
</template>

<script>
import NoteSelectors from "./NoteSelectors";
import NoteEditor from "./NoteEditor";

export default {
  name: "note-container",
  components: {
    NoteSelectors,
    NoteEditor
  }
};
</script>
