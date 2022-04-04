<template>
    <nav>
        <ul>
            <li><Link href="/" preserve-scroll>Home</Link></li>
            <li><Link href="/users" preserve-scroll>Users</Link></li>
            <li><Link href="/settings" preserve-scroll>Settings</Link></li>
            <li>
                <Link href="/logout" method="post" as="button" preserve-scroll
                    >Log out</Link
                >
            </li>
        </ul>
    </nav>
</template>
<script>
import { Link } from "@inertiajs/inertia-vue3";
export default {
    components: {
        Link,
    },
};
</script>
