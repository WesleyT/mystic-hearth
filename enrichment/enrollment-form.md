---
layout: default
title: Enrollment Form
---


<div style="display:flex;justify-content:center;margin:2rem 0;">
  <iframe
    id="enrollForm"
    src="https://docs.google.com/forms/d/e/1FAIpQLScpsWRGN8wwAkQh0WhltfHHEVvAKxXBnM4rI2lIli8ptqtnBQ/viewform?embedded=true"
    width="640"
    height="1200"
    style="max-width:100%;border:none;"
    marginheight="0"
    marginwidth="0">
    Loading…
  </iframe>
</div>

<p style="font-size:0.9rem;color:#555;text-align:center;">
  🔒 Your information will only be used for Mystic Hearth enrollment and communication purposes.
</p>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const iframe = document.getElementById("enrollForm");
    if (!iframe) return;

    let firstLoad = true;
    iframe.addEventListener("load", function () {
      if (firstLoad) { firstLoad = false; return; }
      // On subsequent loads (i.e., after submit showing the thank-you view), scroll up
      window.scrollTo({ top: 0, behavior: "smooth" });
    });
  });
</script>
