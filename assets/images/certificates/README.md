# Certificates Images

This folder contains the images of your certificates for the carousel.

## Required Images

To make the certificate carousel work properly, you need to add the following images:

### Alura Certificates
- `alura-certificate-1.jpg` - Unity 2D Series - Part 1
- `alura-certificate-2.jpg` - Unity 2D Series - Part 2  
- `alura-certificate-3.jpg` - Unity 2D Series - Part 3

### Zenva Certificates
- `zenva-certificate-1.jpg` - Intro to Game Development with Unity
- `zenva-certificate-2.jpg` - Unity Mini-Projects - C# Fundamentals
- `zenva-certificate-3.jpg` - Create Your First 3D Game in Unity
- `zenva-certificate-4.jpg` - Construct a Micro-Farming RPG in Unity

## Image Requirements

- **Format**: JPG or PNG
- **Recommended size**: 400x280 pixels
- **Aspect ratio**: 10:7 (landscape)
- **File size**: Keep under 500KB for fast loading

## How to Add New Certificates

1. Save your certificate image in this folder
2. Update the carousel HTML in `index.html`:
   - Add a new `carousel-item` with your certificate
   - Update the carousel indicators
   - Add the corresponding JavaScript event listener

## Example Structure

```html
<div class="carousel-item">
    <div class="row justify-content-center">
        <div class="col-lg-8">
            <div class="certificate-card fade-in">
                <img src="assets/images/certificates/your-certificate.jpg" alt="Your Certificate" class="certificate-image">
                <h5 class="certificate-title">Your Certificate Title</h5>
                <p class="certificate-description">Certificate description</p>
                <a href="your-certificate-link" target="_blank" class="certificate-link">
                    <i class="fas fa-external-link-alt me-2"></i>View Certificate
                </a>
            </div>
        </div>
    </div>
</div>
```

## Temporary Placeholder

Until you add the actual certificate images, you can use placeholder images or create simple colored rectangles with the certificate information. 