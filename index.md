# Etsy sign-in finished

Copy the code and state below (or the whole address from the address bar) and keep them private. This page sends nothing anywhere.

<pre id="out">If nothing shows here, copy the full address from the address bar.</pre>

<script>var q=new URLSearchParams(location.search);document.getElementById("out").textContent="code: "+(q.get("code")||"(none)")+"\nstate: "+(q.get("state")||"(none)")+"\nerror: "+(q.get("error")||"(none)");</script>
