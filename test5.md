---

title: Title of the post
menu_order: 1
post_status: publish
post_excerpt: This is a post excerpt
featured_image: _images/post-image.jpg
taxonomy:
    category:
        - category-slug-1
        - category-slug-2
    post_tag:
        - tag-1
        - tag-2
custom_fields:
    field1: value 1
    field2: value 2

---

## My post content

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec a lacinia orci.
Nunc sodales massa enim, nec consectetur orci tempus ac.

### Section with image

![alt text for the image](/_images/pic4.jpg "Caption for the image")

Nam rutrum ultricies sapien id rhoncus. In pellentesque efficitur suscipit.
Aliquam vel est consectetur lectus malesuada mollis sit amet non neque. 

### Section with link

This is a [relative link](../sub-dir1/post3.md) which links to another markdown post w.r.t the current file.
This is an [absolute link](/folder1/sub-dir1/post3.md) which links to another post w.r.t the root directory.

### Section with HTML

<section id="home">
    <h2>Welcome to Our Website!</h2>
    <p>This is a sample HTML page with JavaScript and CSS styling.</p>
    <button type="button" onclick="showMessage()">Show message</button>
</section>

<script>
    function showMessage() {
        alert('Thank you for contacting us!');
    }
</script>

<!-- Sample CSS Style -->
<style>
    h1 {
        color: red;
    }
</style>
