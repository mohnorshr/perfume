# NOIR ESSENCE - عطر رجالي فاخر

## 1. Concept & Vision

تجربة حسية رقمية تعكس جوهر الذكاء والأناقة. الموقع يحاكي الغموض والجاذبية من خلال حركات سلسة وانتقالات درامية. الشعور العام: كأنك تدخل صالون عطور فاخر في منتصف الليل - دافئ، غامض، ساحر.

## 2. Design Language

### Aesthetic Direction
**Dark Luxury** - أناقة داكنة مع لمسات ذهبية. يستحضر أجواء العطور الفرنسية الراقية مع لمسة شرقية غامضة.

### Color Palette
- Primary (Deep Black): `#0a0a0a`
- Secondary (Rich Gold): `#c9a962`
- Accent (Amber Glow): `#d4a853`
- Background Gradient: `linear-gradient(135deg, #0a0a0a 0%, #1a1510 50%, #0d0d0d 100%)`
- Text Primary: `#f5f0e8`
- Text Secondary: `rgba(245, 240, 232, 0.6)`
- Glass Effect: `rgba(201, 169, 98, 0.1)`

### Typography
- Headings: **Playfair Display** (serif, elegant, luxurious)
- Arabic: **Tajawal** (modern, readable)
- Body: **Cormorant Garamond** (refined, classic)
- Fallback: Georgia, serif

### Spatial System
- Base unit: 8px
- Section padding: 120px vertical
- Content max-width: 1400px
- Generous whitespace to convey luxury

### Motion Philosophy
- **Cinematic entrances**: العناصر تدخل بتأخير متتابع (staggered)
- **Parallax depth**: طبقات متعددة تتحرك بسرعات مختلفة
- **Floating particles**: جزيئات ذهبية تطفو في الخلفية
- **Magnetic hover**: العناصر تنجذب للماوس
- **Scroll-triggered reveals**: كشف تدريجي مع التمرير
- **Smooth morphing**: انتقالات سلسة بين الحالات

### Visual Assets
- أيقونات: Phosphor Icons (thin style)
- صور: Unsplash للعطور والإضاءة
- تأثيرات: CSS gradients, SVG particles, canvas animations
- زخارف: أنماط هندسية إسلامية كخلفيات

## 3. Layout & Structure

### Hero Section (100vh)
- عرض زجاجة العطر بتأثير 3D tilt
- جزيئات ذهبية متحركة في الخلفية
- عنوان متحرك بحركة reveal
- زر CTA مع glow effect

### Story Section
- نص يتكشف كلمة كلمة عند التمرير
- صورة جانبية مع parallax
- خط ذهبي متحرك يفصل الأقسام

### Features Section
- 3 بطاقات بتأثير glass morphism
- أيقونات متحركة عند hover
- staggered reveal مع التمرير

### Notes Section (Interactive)
- ثلاثة طبقات: Top, Heart, Base
- كل طبقة قابلة للتوسع مع تفاصيل
- ألوان متدرجة تمثل رائحة كل طبقة

### Gallery Section
- صور متداخلة مع hover zoom
- lightbox effect عند النقر
- smooth transitions

### Testimonials
- carousel تلقائي
- اقتباسات مع تأثير typewriter
- نجوم ذهبية متحركة

### CTA Section
- نموذج طلب مع floating labels
- تأثير ripples عند الإرسال
- تأكيد متحرك

### Footer
- معلومات التواصل
- روابط سوشيال ميديا
- خريطة أنماط زخرفية

## 4. Features & Interactions

### Core Features
1. **3D Product Viewer**: زجاجة تدور وتتتفاعل مع الماوس
2. **Floating Particles System**: جزيئات ذهبية تتفاعل مع scroll
3. **Magnetic Buttons**: أزرار تنجذب للمؤشر عند hover
4. **Scroll Animations**: كشف تدريجي لكل عنصر
5. **Parallax Sections**: طبقات متعددة تتحرك بشكل مستقل
6. **Interactive Notes**: استكشاف طبقات الرائحة

### Micro-interactions
- الأزرار: scale + glow عند hover
- البطاقات: lift + shadow عند hover
- الروابط: underline يتوسع من المنتصف
- الأيقونات: rotation خفيف عند hover
- الصور: zoom خفيف مع overlay

### States
- Loading: شاشة splash مع animated logo
- Empty: لا يوجد
- Error: shake animation + رسالة
- Success: confetti + checkmark animation

## 5. Component Inventory

### Navigation
- Fixed transparent → solid on scroll
- Logo on left, links on right
- Hamburger menu on mobile
- States: transparent, solid, mobile-open

### Hero Badge
- "New Collection 2024"
- Gold border animation
- Pulse glow effect

### Product Card
- Glass morphism background
- Image with hover zoom
- Title, price, rating
- Add to cart button
- States: default, hover, active

### Feature Card
- Icon with glow
- Title + description
- Hover: lift + icon animate

### Accordion (Notes)
- Header with +/- icon
- Content with gradient
- Smooth height transition

### Form Input
- Floating label
- Border animation on focus
- Success/error states
- Ripple effect on submit

### Button
- Primary: gold background, dark text
- Secondary: transparent, gold border
- Magnetic effect on hover
- Ripple on click

## 6. Technical Approach

### Stack
- Vanilla HTML5 + CSS3 + JavaScript
- No frameworks (pure performance)
- CSS custom properties for theming
- IntersectionObserver for scroll animations
- RequestAnimationFrame for smooth animations

### Architecture
- Single HTML file
- Embedded CSS (scoped styles)
- Modular JS (class-based components)
- CSS animations + JS for complex interactions

### Performance
- Lazy loading images
- CSS transforms for animations (GPU accelerated)
- Debounced scroll handlers
- Prefers-reduced-motion support

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Graceful degradation for older browsers