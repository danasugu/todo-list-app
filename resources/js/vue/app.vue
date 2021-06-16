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
import listView from "./listView"
  export default {
    components: {
      addItemForm,
      listView
    }
  }
</script scoped>
.todoListContainer {
  width: 350px;
  margin: auto;
}

<style