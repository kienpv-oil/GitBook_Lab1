# Interactive blocks

Ngoài Markdown mặc định mà ta có thể viết, GitBook còn có một số khối tương tác có sẵn mà bạn có thể sử dụng. Ta có thể tìm thấy các khối tương tác bằng cách nhấn / từ trong trình soạn thảo.

<figure><img src="https://gitbookio.github.io/onboarding-template-images/interactive-hero.png" alt=""><figcaption></figcaption></figure>

Dưới đây là một số ví dụ về khối tương tác:

### Tabs

{% tabs %}
{% tab title=" Tab thứ nhất" %}
Mỗi tab giống như một trang nhỏ — nó có thể chứa nhiều block khác nhau, thuộc bất kỳ loại nào. Vì vậy, ta có thể thêm các code block, hình ảnh, interactive block và nhiều loại khác vào các tab riêng lẻ.
{% endtab %}

{% tab title="Tab thứ hai" %}
Add images, blocks, and more.

```python
```
{% endtab %}
{% endtabs %}

### Drawings

<img src="../.gitbook/assets/file.excalidraw.svg" alt="" class="gitbook-drawing">

### Embedded&#x20;

Ta có thể nhúng một ứng dụng nào đó vào Git. Như đây ta tiến hành nhúng youtube:

{% embed url="https://www.youtube.com/watch?v=4NB0NDtOwIQ" %}

