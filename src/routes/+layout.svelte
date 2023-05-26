<script>import "../app.postcss";</script>

<div class="max-w-6xl m-auto">
    <header></header>  
    <main class="mx-8">
        <slot></slot>
    </main>
    <footer class="max-w-2xl m-auto border-t border-black my-8 py-4">
        BoldContacts &bull; <a href="https://boldcontacts.org">https://boldcontacts.org</a> &bull; <a href="info@boldcontacts.org">info@boldcontacts.org</a>
        <p class="text-xs leading-3">
            BoldContacts™ is a trademark of Joel Parker Henderson.
            <br>Copyright © 2022-2023 by Joel Parker Henderson.
            <br>All Rights Reserved.
        </p>
    </footer>
</div>
