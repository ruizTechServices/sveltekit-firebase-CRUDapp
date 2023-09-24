<div class="mainContainer">
    <div class="headerContainer">
        <h1>todoList</h1>
        <button><i class="fa-solid fa-floppy-disk"></i><p>Save</p></button>
    </div>
    <main>
        <div class="enterTodo">
            <input type="text" placeholder="Enter Todo">
            <button>add</button>
        </div>
    </main>
</div>

<style>
    .mainContainer{
        display: flex;
        flex-direction: column;
        min-height: 100vh;
        gap: 24px;
        padding: 24px;
        width: 100%;
        max-width: 1000px;
        margin: 0 auto;
    }
    .headerContainer{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .headerContainer button{
        background: #003c5b;
        color: white;
        padding: 10px 18px;
        border: none;
        border-radius: 5px;
        overflow: hidden;
        font-weight: 700;
        display: flex;
        align-items: center;
        gap: 10px;
    }
    .headerContainer button i{
        font-size: 1.1rem;
    }
    .headerContainer button:hover{
        opacity: 0.7;
        cursor: pointer;
    }
    main{
        display: flex;
        flex-direction: column;
        gap:8px;
        flex: 1;
        justify-content: end;
    }
    .enterTodo{
        display: flex;
        align-items: stretch;
        border: 1px solid #0891b2;
    }
    .enterTodo input{
        background: transparent;
        border: none;
        padding: 14px;
        color: white;
        flex: 1;

    }
    .enterTodo input:focus{
        outline: none;
    }
    .enterTodo button{
        padding: 0 28px;
        background: #003c5b;
        border: none;
        color: cyan;
        font-weight: 600;
        cursor: pointer;
    }
    .enterTodo button:hover{
        background: transparent;
    }
</style>