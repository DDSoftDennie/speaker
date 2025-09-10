# Building Accessible and Inclusive Backends

Accessibility is not only for frontend developers and designers. It is also for backend developers! I know, this is a bold statement. Let's dive into Accessibility and inclusion in backend development.

When designing our backend systems, we have a big impact on the accessibility of our applications. If we want to provide inclusive and accessible options in our frontend there is a need for fields in the backend. Without the right fields in the backend, we can't provide the right options in the frontend.

When making a database and API system that manages images we need to know that we need more than the image itself in bitmap or the uri supporting the image. We also need a text description of the image. This text description is used for screen readers and other assistive technology. If we don't provide this option, the frontend can never provide an accurate text.

When building a backend system that manages user account and we use gender as a binary option, we need to know that this is having an impact on the inclusive options we do want to provide in our frontend.

But as a backend developer we can do even more. We can force people to use the right inclusive and accessible options by designing our backend systems in a way that it only accepts the right options. Uploading an image without a text description? Not possible!

Frontend developers love to use a lot of color. But what if we design our backend systems in a way that it only accepts color combinations that are accessible for people with color blindness?

In this session we go deeper into this and other examples where the backend developer has an impact and can enforce accessibility and inclusion.

[Back](Accessibility.md)
