<template>
  <div class="navbar bg-base-100 shadow-sm">
  <div class="navbar-start">
    <div class="dropdown">
      <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /> </svg>
      </div>
      </div>
      <img
      style="height: 50px;"
      src="../../public/logotp.png"
    >
    <a class="btn btn-ghost text-xl" style="color: #5865f2;">LaunchPad Framework</a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-horizontal px-1">
      <li>
        <details>
          <summary>Docs</summary>
          <ul class="p-2">
            <li style="font-size: 12px; color: #5865f2;"><a>Quick Start</a></li>
            <li style="font-size: 12px;"><a>Guide</a></li>
            <li style="font-size: 12px;"><a>Tutorial</a></li>
            <li style="font-size: 12px;"><a>Examples</a></li>
            <li style="font-size: 12px;"><a>Glossary</a></li>
            <li style="font-size: 12px;"><a>Error References</a></li>
          </ul>
        </details>
      </li>
      <li><a>API</a></li>
      <li>
        <details>
          <summary>Ecosystem</summary>
          <ul class="p-1">
            <li style="color: gray; font-size: 9px; font-style: bold">RESOURCES</li>
            <li style="font-size: 12px;"><a>Partners</a></li>
            <li style="font-size: 12px;"><a>Developers</a></li>
            <li style="font-size: 12px;"><a>Jobs</a></li>
            <li style="font-size: 12px;"><a>Sponsors</a></li>
            <li style="color: gray; font-size: 9px; font-style: bold">HELP</li>
            <li style="font-size: 12px;"><a>Discord Server</a></li>
            <li style="font-size: 12px;"><a>GitHub Discussions</a></li>
            <li style="color: gray; font-size: 9px; font-style: bold">NEWS</li>
            <li style="font-size: 12px;"><a>Blogs</a></li>
            <li style="font-size: 12px;"><a>Events</a></li>
            <li style="font-size: 12px;"><a>Podcasts</a></li>
            <li style="font-size: 12px;"><a>Newsletters</a></li>
          </ul>
        </details>
      </li>
      <li>
        <details>
          <summary>About</summary>
          <ul class="p-2">
            <li style="font-size: 12px;"><a>FAQ</a></li>
            <li style="font-size: 12px;"><a>The Team</a></li>
            <li style="font-size: 12px;"><a>Releases</a></li>
            <li style="font-size: 12px;"><a>Community Guide</a></li>
            <li style="font-size: 12px;"><a>Code Of Conduct</a></li>
            <li style="font-size: 12px;"><a>Privacy Policy</a></li>
          </ul>
        </details>
      </li>
      <li style="color: #5865f2;"><a>Sponsor</a></li>

    </ul>
  </div>
  <div class="divider lg:divider-horizontal"></div>
  <label class="toggle text-base-content">
  <input type="checkbox" value="light" class="theme-controller" />
  
  <svg aria-label="moon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g stroke-linejoin="round" stroke-linecap="round" stroke-width="2" fill="none" stroke="currentColor"><path d="M12 3a6 6 0 0 0 9 9 9 9 0 1 1-9-9Z"></path></g></svg>
  <svg aria-label="sun" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g stroke-linejoin="round" stroke-linecap="round" stroke-width="2" fill="none" stroke="currentColor"><circle cx="12" cy="12" r="4"></circle><path d="M12 2v2"></path><path d="M12 20v2"></path><path d="m4.93 4.93 1.41 1.41"></path><path d="m17.66 17.66 1.41 1.41"></path><path d="M2 12h2"></path><path d="M20 12h2"></path><path d="m6.34 17.66-1.41 1.41"></path><path d="m19.07 4.93-1.41 1.41"></path></g></svg>

</label>
  <div class="navbar-end">
</div>
</div>
</template>