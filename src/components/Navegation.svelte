<script>
 import { Link } from 'svelte-routing';
 import codo from '../../public/codo.png'
</script>

<nav>
    <img src={codo} alt="logo de codo a codo" class="logo-client">
    <ul>
        <li>
            <Link to='/'>Home</Link>
        </li>
        <li>
            <Link to='/avances'>Avances</Link>
        </li>
        <li>
            <Link to='/aprende'>Aprende</Link>
        </li>
    </ul>
</nav>

<style>
    .logo-client{
        width: 80px;
    }
   nav{
    position: relative;
    top: 20px;
    left: 50%;
    transform: translateX(-50%);
    width: 500px;
    background: rgba(255, 255, 255, 0.4);
    
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 30px;
    border-radius: 20px;
   }

   ul{
    display: flex;
    flex-direction: row;
    list-style: none;
    gap: 20px;
   }
</style>