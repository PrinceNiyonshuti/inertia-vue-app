<template>
    <nav class="mt-6">
        <ul class="list-disc">
            <li>
                <NavLink href="/" :active="$page.component == 'Home'">
                    Home
                </NavLink>
            </li>
            <li>
                <NavLink href="/users" :active="$page.component == 'Users'">
                    Users
                </NavLink>
            </li>
            <li>
                <NavLink
                    href="/settings"
                    :active="$page.component == 'Settings'"
                >
                    Settings
                </NavLink>
            </li>
            <li>
                <Link
                    href="/logout"
                    method="post"
                    as="button"
                    class="text-blue-500 hover:underline"
                    preserve-scroll
                    >Log out</Link
                >
            </li>
        </ul>
    </nav>
</template>
<script>
import NavLink from "./NavLink.vue";
export default {
    components: {
        NavLink,
    },
};
</script>
