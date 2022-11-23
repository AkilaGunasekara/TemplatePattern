<h1>Template Pattern</h1>
In Template pattern, an abstract class exposes defined way(s)/template(s) to execute its methods. Its subclasses can override the method implementation as per need but the invocation is to be in the same way as defined by an abstract class. <br>This pattern comes under behavior pattern category.

<h2>Implementation</h2>
We are going to create a Game abstract class defining operations with a template method set to be final so that it cannot be overridden.<br> Cricket and Football are concrete classes that extend Game and override its methods.

TemplatePatternDemo, our demo class, will use Game to demonstrate use of template pattern.

![template_pattern_uml_diagram](https://user-images.githubusercontent.com/79799727/203539408-ec73820d-0520-47ff-828c-9fc5add57e65.jpeg)
