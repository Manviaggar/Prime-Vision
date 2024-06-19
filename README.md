# Enhanced Shopping Experience with Visual AI

## Introduction

Think about the iconic yellow saree worn by Kajol in *Dilwale Dulhania Le Jayenge* or the stylish sunglasses sported by Ranveer Singh in *Gully Boy*. These Bollywood movies, available on Amazon Prime, have set significant fashion trends in India and beyond. Yet, while AI is revolutionizing various sectors, its potential in enhancing our shopping experiences remains largely untapped.

Our project aims to bridge this gap by leveraging visual AI technology to improve product search, recommendations, and item identification in text, images, or video content. By extending the X-ray feature from Amazon Prime Video, we enable users to identify and directly purchase items featured in video content, such as furniture, clothing, and other products. This integration of AI and e-commerce creates a seamless, personalized, and engaging shopping experience.

## Features

1. **Real-Time Object Detection in Videos**:
    - Users can upload videos and get real-time detection of various objects.
    - Detected objects are highlighted with bounding boxes and labeled with their respective names.

2. **Product Recommendations**:
    - Each detected object is linked to relevant products on Amazon.
    - Users can click on these links to view and purchase similar items.

3. **Enhanced Search Functionalities**:
    - Improve search accuracy and relevance by integrating visual recognition with traditional text-based search.
    - Personalized product recommendations based on detected items in the user’s content.

## Project Structure

- **HTML/CSS**: Frontend interface for video upload, playback, and displaying detection results.
- **JavaScript**: Handles video processing, object detection, and communication with the Web Worker.
- **Web Worker**: Offloads heavy computations to a separate thread to keep the UI responsive.
- **ONNX Runtime for WebAssembly**: Runs the YOLOv8 model for object detection within the Web Worker.

## Getting Started

### Prerequisites

- Modern web browser (e.g., Chrome, Firefox)
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. Clone the repository:
   ```bash
   git clone [link]
2. Open index.html in your web browser.

###  Usage

1.  Upload a video using the "Upload Video" button.
2.  Play the video to see real-time object detection.
3.  Click on the highlighted objects to view related products on Amazon.

###  Impact
   Our project aims to revolutionize the shopping experience by:

  - **Increasing Engagement**: By allowing users to interact with video content and easily purchase featured items, we create a more engaging and immersive experience.
  - **Boosting Sales**: Direct links to purchase items from videos can significantly increase conversion rates and sales.
  - **Setting Trends**: Leveraging popular movies and videos to set new trends in fashion and accessories.

###  Business Relevance

  - **Market Expansion**: Tap into new customer segments who are influenced by visual media.
  - **Enhanced Customer Experience**: Providing a seamless integration of shopping with entertainment, leading to higher customer satisfaction and loyalty.
- **Competitive Advantage**: Stand out in the e-commerce market by offering advanced, AI-driven shopping features.

###  Improvements for the Future

  -  **Advanced Search Integration**: Improve the search algorithm to prioritize similar products at the top of the search results.
  -  **Expanding Object Detection**: Increase the range of detectable objects beyond the current 80 classes.
-  **Improved Accuracy**: Enhance the model's accuracy in identifying and recommending products.
  -  **User Feedback Loop**: Implement a system to gather user feedback and refine recommendations based on user preferences and behaviors.
    - **Augmented Reality Integration**: Allow users to visualize how products will look in their own space using AR technology.

### Conclusion

This project demonstrates the potential of integrating visual AI technology to enhance the shopping experience, transforming how consumers interact with video content and e-commerce platforms. By harnessing the influential power of movies and leveraging AI, we aim to create a more personalized, seamless, and engaging shopping journey across various product categories

