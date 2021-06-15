    <template>
        <div class="todoListContainer">
        <div class="heading">
          <h2 id="title">Todo list</h2>
          <add-item-form />
        </div>
        </div>
    </template>

<script>
import addItemForm from "./addItemForm"
  export default {
    componentsL {
      addItemForm
    }
  }
</script>