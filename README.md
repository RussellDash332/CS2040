# CS2040

Collection of CS2040(S) PYPs - last updated **23 February 2026**

Full repository: [https://github.com/RussellDash332/CS2040](https://github.com/RussellDash332/CS2040)

My own tutorial slides: [https://github.com/RussellDash332/slides/tree/main/CS2040](https://github.com/RussellDash332/slides/tree/main/CS2040)

## Midterms

{% include midterms.md %}

## Finals

{% include finals.md %}

## Contributing

Just submit a pull request! Ensure that you have updated the links in the `_includes` folder.

RussellDash332 &copy; 2026

<script>
document.querySelectorAll("h1, h2, h3, h4, h5, h6").forEach(function(h) {
  if (!h.id) return;
  let a = document.createElement("a");
  a.href = "#" + h.id;
  a.className = "anchor";
  a.textContent = "¶";
  h.appendChild(a);
});
</script>