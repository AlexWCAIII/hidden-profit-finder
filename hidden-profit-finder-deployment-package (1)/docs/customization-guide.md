# Customization Guide - Hidden Profit Finder™

## 🎯 Business Owner's Guide to Content Updates

This guide shows you how to make content changes without technical expertise. All changes are made by editing the `index.html` file in a text editor.

## 📝 Basic Content Updates

### Updating Your Contact Information

**Find this section in index.html:**
```html
<p>Wilts Alexander<br>
Evidence-Based Strategy Coaching™</p>
```

**Change to:**
- Your name and title
- Your company tagline or credentials
- Your phone number and email

### Updating the Calendly Link

**Find this line:**
```html
href="https://calendly.com/coachwiltsalexander/30min"
```

**Replace with your Calendly URL:**
- Get your Calendly booking link
- Replace the entire URL between the quotes

### Updating the Case Study

**Find the manufacturing example:**
```html
<h4>Example A — Cut Costs without Cutting People (Manufacturing, $8M rev)</h4>
```

**Customize with your data:**
- Change industry and revenue size
- Update the situation description
- Modify the results to match your experience

## 🎨 Visual Customization

### Changing Colors

**Find the CSS section (near top of file):**
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
}
```

**Update brand colors:**
- Replace hex codes with your brand colors
- Use online color picker to find hex codes
- Test on mobile after changes

### Updating Images

**Current placeholder images can be replaced:**
1. **Upload your images** to image hosting service
2. **Copy the image URLs**
3. **Replace placeholder URLs** in the HTML
4. **Test loading speed** after changes

### Logo Integration

**To add your company logo:**
1. **Upload logo** to image hosting (Imgur, Dropbox, etc.)
2. **Find the header section** in HTML
3. **Add logo image tag** before the headline
4. **Ensure mobile responsiveness**

## 📊 Business Content Updates

### Updating Value Propositions

**Main headline section:**
```html
<h1>Stop Leaving Money on the Table</h1>
<h2>Discover Hidden Profits in Your Business</h2>
```

**Customize messaging:**
- Align with your unique positioning
- Match your brand voice and tone
- Keep benefit-focused language

### Social Proof Updates

**Add your testimonials:**
1. **Replace manufacturing example** with your case study
2. **Add client logos** (with permission)
3. **Include specific metrics** and results
4. **Use real client quotes** where possible

### Call-to-Action Optimization

**Button text optimization:**
```html
<button>Run Free Hidden Profit Finder</button>
```

**A/B test different versions:**
- "Find My Hidden Profits"
- "Discover Profit Opportunities"
- "Start Profit Analysis"
- "Get My Profit Report"

## 🔧 Advanced Customizations

### Adding Google Analytics

**Insert before closing `</head>` tag:**
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_TRACKING_ID');
</script>
```

**Replace `YOUR_TRACKING_ID`** with your Google Analytics ID.

### Lead Form Integration

**Current form sends to Netlify:**
- Submissions appear in your Netlify dashboard
- **To integrate with your CRM**: Replace form action URL
- **Popular integrations**: HubSpot, Salesforce, ActiveCampaign

### Performance Optimization

**Image optimization:**
1. **Compress images** before uploading (TinyPNG.com)
2. **Use WebP format** for faster loading
3. **Add lazy loading** for images below fold
4. **Test mobile speed** regularly

## 📱 Mobile Optimization

### Testing Mobile Experience

**Essential mobile checks:**
- [ ] Text is readable without zooming
- [ ] Buttons are easily tappable
- [ ] Forms work properly on mobile keyboards  
- [ ] Loading speed is under 3 seconds on 3G
- [ ] All links function correctly

### Mobile-Specific Updates

**Adjust mobile headlines:**
- Shorter headlines for small screens
- Larger button text for finger tapping
- Simplified navigation for mobile users
- Touch-friendly spacing between elements

## 🚀 Content Strategy Updates

### Seasonal Campaigns

**Update messaging for different periods:**
- **Q4**: "End-of-year profit optimization"
- **Q1**: "New year efficiency improvements"
- **Mid-year**: "Half-year performance review"
- **Budget season**: "Budget planning with data"

### Industry Customization

**Tailor content for specific verticals:**
- **Manufacturing**: Focus on operational efficiency
- **Professional Services**: Emphasize billable hour optimization
- **Retail**: Highlight inventory and margin improvements
- **Healthcare**: Focus on patient outcomes and cost reduction

## 📊 Performance Tracking

### Content Performance Metrics

**Track these improvements:**
- **Conversion rate**: Form submissions per visitor
- **Time on page**: Engagement with your content
- **Mobile vs desktop**: Device-specific performance
- **Source tracking**: Which emails/campaigns work best

### A/B Testing Ideas

**Test different versions:**
1. **Headlines**: Benefit-focused vs. feature-focused
2. **CTA buttons**: Color, text, and positioning  
3. **Social proof**: Different case studies or testimonials
4. **Form length**: Minimize fields for higher conversion

---

**🎯 Remember: Small changes can have big impacts. Test one element at a time and measure results before making additional changes.**
