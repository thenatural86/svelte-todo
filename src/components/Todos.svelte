<script>
    import Todo from "./Todo.svelte"
</script>
<!-- List of actual todos -->
<div class="app-body">
    <ul>
        <Todo />

        <!-- <li class="todo-list list-item-view completed"> -->
        <!-- <div class="list-item-view"> -->
            <!-- <span>
                <button class="btn btn-done">
                    <i class="fa-solid fa-check-square">
                    </i>
            </button>
            <span>First Todo</span>
            </span>
            <button class="btn btn-delete fa-solid fa-trash">
            </button> -->
    <!-- </div> -->
        <!-- </li> -->
    </ul>
</div>

<style>
    ul {
    list-style-type: none;
    -webkit-padding-start: 0;
    padding-left: 0px;
    }

.app-body {
            flex-grow: 1;
            max-height: 600px;
            overflow-x: hidden;
        }



</style>
