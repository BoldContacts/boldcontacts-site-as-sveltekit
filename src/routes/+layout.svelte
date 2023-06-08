<script>
    import "../app.postcss";
</script>

<div class="max-w-screen-sm m-auto">
    <header class="m-auto border-b border-black mb-8 py-4">
        <nav class="flex justify-between">
            <a class="nav-a" href="/"><b>BoldContacts</b></a>
            <a class="nav-a" href="https://apps.apple.com/us/app/boldcontacts/id6443335501">App</a> 
            <a class="nav-a" href="/training">Training</a> 
            <a class="nav-a" href="/roadmap">Roadmap</a> 
            <a class="nav-a" href="https://github.com/orgs/BoldContacts/repositories">GitHub</a> 
            <a class="nav-a" href="mailto:info@boldcontacts.org">Email</a>
        </nav>
    </header>  
    <main class="">
        <slot></slot>
    </main>
    <footer class="m-auto border-t border-black my-8 py-4">
        <nav class="flex justify-between">
            <a class="nav-a" href="/"><b>BoldContacts</b></a>
            <a class="nav-a" href="https://apps.apple.com/us/app/boldcontacts/id6443335501">App</a> 
            <a class="nav-a" href="/training">Training</a> 
            <a class="nav-a" href="/roadmap">Roadmap</a> 
            <a class="nav-a" href="https://github.com/boldcontacts">GitHub</a> 
            <a class="nav-a" href="mailto:info@boldcontacts.org">Email</a>
        </nav>
        <p class="text-xs leading-3">
            BoldContacts™ is a trademark of Joel Parker Henderson.
            <br>Copyright © 2022-2023 by Joel Parker Henderson.
            <br>All Rights Reserved.
        </p>
    </footer>
</div>
