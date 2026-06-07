<script lang="ts">
    import Logo from "$lib/assets/logoText.svg";
    import { Button } from "$lib/components/ui/button/index.js";
</script>

<header class="  bg-white text-black p-2 shadow-sm">
    <div class="mx-4 flex items-center">
        <div>
            <img src={Logo} alt="Logo" class="h-6" />
        </div>
        <ul class="mx-auto flex space-x-8">
            <li>
                <a href="/" class="hover:underline">Home</a>
            </li>
            <li>
                <a href="/products" class="hover:underline">Products</a>
            </li>   
            <li>
                <a href="/about" class="hover:underline">About</a>
            </li>
            <li>
                <a href="/contact" class="hover:underline">Contact</a>
            </li>
        </ul>
        <div>
            <Button variant="outline" class="mr-2">
                <a href="/signup">Sign Up</a>
            </Button>
            <Button>
                <a href="/login">Login</a>
            </Button>
        </div>
    </div>
</header>
