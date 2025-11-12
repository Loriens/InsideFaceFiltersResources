# Inside Face Filters: Vision, Segmentation, and Shaders in Action

**[🎥 View Talk at Mobius 2025 Autumn](https://mobiusconf.com/en/talks/feab09f6d9d0402782c1cef15df27147/)**

Usually, an iOS developer implements UI and works with APIs, but what lies beyond such tasks?

There is the world of computer vision and graphics, where mathematics ceases to be abstract: linear algebra and trigonometry bring facial expressions to life, while optimization transforms into GPU shaders.

In the talk, we will break down how face filters work under the hood: from face tracking and segmentation through Core ML to realistic filters.

**We will cover two approaches:**

1. **Based on face landmarks** with point-wise processing of different facial zones.
2. **Based on segmentation models** with color processing of different segments.

Special attention will be paid to the technical implementation: how Vision works, how segmentation Core ML models are structured, and how to write custom shaders for CIKernel to achieve maximum performance.

## Resources

### Example Project

- [FaceFXKit](https://github.com/Loriens/FaceFXKit)

### Books

- [Master Photo and Video Editing with Metal: A Practical Approach to Leveraging Metal Media Editing Software](https://www.amazon.com/Master-Photo-Video-Editing-Metal/dp/B0DBTTQPRC)
- [Core Image for Swift. Advanced Image Processing for iOS](https://books.apple.com/us/book/core-image-for-swift/id1073029980)

### Apple Documentation

- [Vision Framework](https://developer.apple.com/documentation/vision)
- [Core ML Framework](https://developer.apple.com/documentation/coreml)
- [Metal](https://developer.apple.com/documentation/Metal/)
- [Analyzing a selfie and visualizing its content](https://developer.apple.com/documentation/vision/analyzing-a-selfie-and-visualizing-its-content)
- [Face Detection](https://developer.apple.com/documentation/vision/detectfacerectanglesrequest)
- [Face Landmarks Detection](https://developer.apple.com/documentation/vision/detectfacelandmarksrequest)
- [NormalizedPoint](https://developer.apple.com/documentation/vision/normalizedpoint)
- [NormalizedRect](https://developer.apple.com/documentation/vision/normalizedrect)

### Segmentation Model

- [Face Parsing](https://github.com/yakhyo/face-parsing)

### Other

- [Easings Functions](https://easings.net/)

---

## Contact

Feel free to reach out for questions or discussions about the talk.

**Telegram:** [@loriens](https://t.me/loriens)
