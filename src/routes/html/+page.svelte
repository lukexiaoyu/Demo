<script>
    let a=''
    let open=false
</script>
<main>
    <dialog {open}>
        <p>Greetings, one and all!</p>
        <button on:click={()=>{open=!open}}>OK</button>
      </dialog>

      <button on:click={()=>{open=!open}}>open</button>
      <address>
        <a href="mailto:814008000@163.com">jim@rock.com</a><br>
        <a href="tel:+18936518839">(311) 555-2368</a>
      </address>
</main>
<style></style>