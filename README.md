NAMA : ABDAN HAFIDZ
NRP : 5054231021

Tautan Website : https://abdanhafidz.com/online-resto
![image](https://github.com/user-attachments/assets/8ccc75fc-534c-4894-9ef5-3501c81e2bd2)
![image](https://github.com/user-attachments/assets/a0d41c48-6f45-46f0-9519-f296e61dd89a)

# Documentation of Japanese Resto Website Implementation

## 1. Basic HTML5 Structure

### 1.1 Document Declaration
```html
<!DOCTYPE html>
<html lang="en">
```
- Using `<!DOCTYPE html>` to define the HTML5 document
- Adding `lang="en"` attribute to specify the English language

### 1.2 Metadata
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sakura Warung - Japanese Cuisine</title>
</head>
```
- `charset="UTF-8"` to support international characters
- `viewport` meta tag for mobile responsiveness

## 2. Semantic HTML5 Elements

### 2.1 Semantic Structure
- `<header>`: Website header section
- `<nav>`: Main navigation
- `<section>`: Main content division
- `<footer>`: Website footer section

#### Implementation Example
```html
<header>
    <div class="container">
        <h1>🍜 Sakura Warung</h1>
    </div>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
</nav>
```

## 3. Accessibility and SEO

### 3.1 Best Practices
- Using structured headings
- Providing `alt` text for images
- Utilizing semantic elements

#### Example
```html
<img src="ramen.jpg" alt="Special Ramen with Meat Toppings" />
```

## 4. Responsive Design

### 4.1 Responsive Techniques
- Using CSS Flexbox and Grid
- Media queries for screen adaptation
- Relative units (`%`, `em`, `rem`)

#### Media Query Example
```css
@media (max-width: 768px) {
    nav a {
        display: block;
        margin: 10px 0;
    }
}
```

## 5. External Resources Integration

### 5.1 Font Awesome
```html
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
```
- Using CDN for icons
- Facilitates the use of social media icons

## 6. Performance and Optimization

### 6.1 Optimization Strategies
- Optimized image size and format
- Minimal inline styling
- Using `object-fit` for images

## 7. Validation and Standards

### 7.1 HTML5 Standards
- Valid document structure
- No deprecated tags used
- Consideration of semantics and accessibility

## Conclusion

The website implementation utilizes modern HTML5 features:
- Clear semantics
- Responsive
- Accessible
- Optimal performance

### Further Recommendations
- Consider using Web Components
- Implement lazy loading for images
- Optimize Critical Rendering Path
