---
layout: default
title: Members
permalink: /members/
description: Latest news and updates from Sir Bevis Lodge.
# hero_image: /assets/images/lodge.jpg
# hero_alt: Our Lodge Hall - Southampton
hero_image: /assets/images/temple.jpg
hero_alt: Sir Bevis Lodge Hall interior - Southampton Temple
---

<script>
const password = "sirbevis1929";

if (sessionStorage.getItem("siteAuth") !== "true") {
  const entered = prompt("Enter password:");
  if (entered === password) {
    sessionStorage.setItem("siteAuth", "true");
  } else {
    document.body.innerHTML = "<h1>Access denied</h1><p>Ask at lodge for the password</p>";
  }
}
</script>

# Members

Welcome to the members area:
- Meeting minutes
- Officer list
- Dining list
- Members folder

