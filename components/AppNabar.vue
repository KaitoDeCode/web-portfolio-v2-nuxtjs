<template>
    <div class="flex fixed left-1/2 -translate-x-1/2 gap-5 bottom-10">
        <nuxt-link to="/" active-class="flex flex-col items-center bg-black text-white w-12 h-12 rounded-md p-1"   class="flex flex-col items-center  w-12 h-12 rounded-md p-1">
            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 256 256"><path fill="currentColor" d="m221.56 100.85l-79.95-75.47l-.16-.15a19.93 19.93 0 0 0-26.91 0l-.17.15l-79.93 75.47a20.07 20.07 0 0 0-6.44 14.7V208a20 20 0 0 0 20 20h48a20 20 0 0 0 20-20v-44h24v44a20 20 0 0 0 20 20h48a20 20 0 0 0 20-20v-92.45a20.07 20.07 0 0 0-6.44-14.7M204 204h-40v-44a20 20 0 0 0-20-20h-32a20 20 0 0 0-20 20v44H52v-86.72l76-71.75l76 71.75Z"/></svg>
            <span class="text-sm">Home</span>
        </nuxt-link>
        <nuxt-link to="/about" active-class="flex flex-col items-center bg-black text-white"   class="flex flex-col items-center  w-12 h-12 rounded-md p-1">
            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24"><path fill="currentColor" d="M5.85 17.1q1.275-.975 2.85-1.537T12 15q1.725 0 3.3.563t2.85 1.537q.875-1.025 1.363-2.325T20 12q0-3.325-2.337-5.663T12 4Q8.675 4 6.337 6.338T4 12q0 1.475.488 2.775T5.85 17.1M12 13q-1.475 0-2.488-1.012T8.5 9.5q0-1.475 1.013-2.488T12 6q1.475 0 2.488 1.013T15.5 9.5q0 1.475-1.012 2.488T12 13m0 9q-2.075 0-3.9-.788t-3.175-2.137q-1.35-1.35-2.137-3.175T2 12q0-2.075.788-3.9t2.137-3.175q1.35-1.35 3.175-2.137T12 2q2.075 0 3.9.788t3.175 2.137q1.35 1.35 2.138 3.175T22 12q0 2.075-.788 3.9t-2.137 3.175q-1.35 1.35-3.175 2.138T12 22"/></svg>
            <span class="text-sm">About</span>
        </nuxt-link>
        <nuxt-link to="/project" active-class="flex flex-col items-center bg-black text-white p-1"   class="flex flex-col items-center  w-12 h-12 rounded-md p-1">
            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 576 512"><path fill="currentColor" d="M0 80c0-26.5 21.5-48 48-48h96c26.5 0 48 21.5 48 48v16h192V80c0-26.5 21.5-48 48-48h96c26.5 0 48 21.5 48 48v96c0 26.5-21.5 48-48 48h-96c-26.5 0-48-21.5-48-48v-16H192v16c0 1.7-.1 3.4-.3 5L272 288h96c26.5 0 48 21.5 48 48v96c0 26.5-21.5 48-48 48h-96c-26.5 0-48-21.5-48-48v-96c0-1.7.1-3.4.3-5L144 224H48c-26.5 0-48-21.5-48-48z"/></svg>
            <span class="text-sm">Project</span>
        </nuxt-link>
        <nuxt-link to="/contact" active-class="flex flex-col items-center bg-black text-white p-1"   class="flex flex-col items-center  w-12 h-12 rounded-md p-1">
            <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 15 15"><path fill="currentColor" fill-rule="evenodd" d="M11 2H4V0H3v2H1.5A1.5 1.5 0 0 0 0 3.5v8A1.5 1.5 0 0 0 1.5 13h12a1.5 1.5 0 0 0 1.5-1.5v-8A1.5 1.5 0 0 0 13.5 2H12V0h-1zM3 6a2 2 0 1 1 4 0a2 2 0 0 1-4 0m-.618 4.618a2.927 2.927 0 0 1 5.236 0l.33.658A.5.5 0 0 1 7.5 12h-5a.5.5 0 0 1-.447-.724zM9 6h3V5H9zm0 3h3V8H9z" clip-rule="evenodd"/><path fill="currentColor" d="M15 14v1H0v-1z"/></svg>
            <span class="text-sm">Contact</span>
        </nuxt-link>
        <nuxt-link to="/blog" active-class="flex flex-col items-center bg-black text-white"   class="flex flex-col items-center  w-12 h-12 rounded-md p-1">
            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 1000 1000"><path fill="currentColor" d="M196.099.156C88.379.156.219 88.317.219 196.036v607.851c0 107.72 88.16 195.849 195.88 195.849H803.95c107.72 0 195.849-88.129 195.849-195.849V196.036C999.799 88.316 911.67.156 803.95.156zm338.012 186.777c94.026 7.596 148.647 68.316 155.146 145.948c5.05 39.953 3.637 69.6-2.127 91.418c53.633 1.773 116.39 25.822 120.388 113.098v85.911c-5.561 75.026-32.259 167.679-169.225 187.339c-30.84 4.427-65.452 1.464-110.345 1.157c-45.139-1.19-84.496-.975-118.917-.344c-138.941 2.545-215.468-58.535-216.185-189.28c-1.116-44.494.65-92.734.501-152.581c-.558-37.925-.768-77.544.094-114.381c.267-7.189-.671-15.069 1.22-22.807c5.98-84.295 73.682-133.698 152.706-144.665l186.745-.814zM377.963 304.192c-80.036 13.104-83.991 104.44 0 115.726h151.924c80.036-13.104 83.991-104.44 0-115.726zm-34.508 252.82c-82.395 12.791-83.607 116.536 2.941 127.271l279.1 1.001c81.695-12.682 81.454-116.322-2.941-127.302z"/></svg>
            <span class="text-sm">Blog</span>
        </nuxt-link>
    </div>
</template>