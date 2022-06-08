<script>
    import TodoItem from"../lib/todo-item.svelte" // "../" up directory, "$" finds folder

    const title = "Todo";
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>

<form action="" method="">
    <input type="text" name="test" aria-label="Add a todo" placeholder="+ type to add a todo">
</form>

<TodoItem />
<TodoItem />
<TodoItem />
