<script>
    let headingOne = 'Welcome';
    let title = 'About';
    let message = 'type something here ...'

    function updateTitle() {
        title = 'Goodbye';
    }
</script>

<h1>{headingOne}</h1>
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Explicabo cupiditate quo repellat atque nobis minus aliquam. Eius doloremque laborum architecto consectetur iusto ab consequuntur? Repellat explicabo officiis animi maxime temporibus.</p>

<h2>{title}</h2>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem a quos perferendis dignissimos eos similique illo nostrum, officia mollitia iure nam, molestiae libero minus! Eius cupiditate tempore a quae. Aut ab nam delectus, at similique inventore saepe error hic quasi.</p>

<button on:click={updateTitle}>Click me!</button>
<br><br><br>

<input type="text" bind:value={message}>

<p>{message}</p>
