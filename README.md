
This code will be able to click the anchor tag into another page and scrolls down to specific section
<script>
    document.addEventListener("DOMContentLoaded", () => {
    // Check URL for ?scroll=section2
    const params = new URLSearchParams(window.location.search);
    const section = params.get("scroll");

    if (section) {
        const target = document.getElementById(section);
            if (target) {
            target.scrollIntoView({ behavior: "smooth" });
            }
        }
    });
</script>
