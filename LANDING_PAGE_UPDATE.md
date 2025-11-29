# Landing Page Styling Update

The default CTFd landing page HTML has been styled with modern, interactive elements. The CSS styling in `assets/scss/main.scss` includes the `.landing-hero` class.

## HTML Structure

Wrap your default landing page content with the `.landing-hero` class like this:

```html
<div class="landing-hero">
  <div class="landing-content">
    <div class="landing-logo">
      <img class="w-100 mx-auto d-block" style="max-width: 500px;" src="/themes/core/static/img/logo.png?d=a056909d" />
    </div>

    <div class="landing-text">
      <h3>
        <p>A cool CTF platform from <a href="https://ctfd.io">ctfd.io</a></p>
        <p>Follow us on social media:</p>
        <div class="social-links">
          <a href="https://twitter.com/ctfdio" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
          <a href="https://facebook.com/ctfdio" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
          <a href="https://github.com/ctfd" aria-label="GitHub"><i class="fab fa-github"></i></a>
        </div>
      </h3>
    </div>

    <h4>
      <a href="admin">Click here</a> to login and setup your CTF
    </h4>
  </div>
</div>
```

## Features Included

### 1. **Hero Section Background**
- Animated gradient background with smooth pulsing effect
- Floating orb animation in the background for depth
- Modern, futuristic atmosphere

### 2. **Logo Animation**
- Floating animation (bobs up and down)
- Hover effect with scale and enhanced shadow
- Drop shadow with purple glow

### 3. **Typography & Text Styling**
- Gradient text for the first paragraph using purple-to-blue gradient
- Smooth entrance animations (slide down effect)
- Proper color contrast and readability

### 4. **Social Links**
- Circular button design with 60px diameter
- Hover effects with:
  - Ripple/fill animation
  - Color transitions
  - Glow effect with box shadow
  - Icon scale animation
- Responsive layout with proper spacing

### 5. **Call-to-Action Button**
- Gradient background (purple to blue)
- Rounded pill shape (border-radius: 50px)
- Hover effects:
  - Lift animation (translateY)
  - Enhanced shadow
  - Gradient reversal
- Active state with subtle press effect

### 6. **Animations**
- **heroGlow**: Subtle pulsing background animation (8s)
- **float**: Floating orb background animation (20s)
- **floatLogo**: Logo bobbing animation (3s)
- **slideDown**: Text entrance animation
- **fadeInUp**: Content fade-in animation
- **fadeIn**: General fade-in effect

## Customization

You can customize the colors in the CSS:
- Primary color: `#667eea` (blue)
- Secondary color: `#764ba2` (purple)
- Success color: `#00d140` (green)

All animations use CSS3 and are GPU-accelerated for smooth performance.

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Graceful degradation on older browsers
- Responsive design for mobile to desktop
