    <template>
        <div class="todoListContainer">
        <div class="heading">
          <h2 id="title">Todo list</h2>
          <add-item-form />
        </div>
        <list-view />
        </div>
    </template>

<script>
import addItemForm from "./addItemForm"
import listView from "./listView"
import ListView from './listView.vue'
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

.heading {
  background: #e6e6e6;
padding: 10px;
}

#title {
  text-align: center;
}