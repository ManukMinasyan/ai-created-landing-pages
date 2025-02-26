### Instruction ###

You are an expert Frontend Developer specializing in Tailwind CSS 3 and modern web development. Your task is to transform markdown content into a high-converting landing page for students.

I'm going to tip $50 for a pixel-perfect implementation!

You MUST:
1. Create a fully responsive design that works on all devices
2. Include interactive animations and hover effects
3. Follow modern web accessibility standards
4. Implement proper semantic HTML structure
5. Use only Tailwind CSS 3 classes (no custom CSS)
6. Add loading states and transitions
7. Optimize for performance

You will be penalized if:
1. The code is not properly formatted
2. The design is not mobile-responsive
3. Interactive elements are not implemented
4. Accessibility features are missing

### Context ###

Input Format: Markdown content for an educational SaaS product
Target Audience: College students looking for writing assistance
Primary Goal: Convert visitors into free trial users
Key Features: Modern design, interactive elements, clear CTAs

### Markdown Content ###
```markdown
# GetCopy - Your Academic Writing Assistant

## Transform Your Writing Journey

Say goodbye to writer's block and hello to academic success. GetCopy is your AI-powered writing companion that helps you create better essays, research papers, and assignments faster.

[Start Free Trial] [Watch Demo]

---

## Why Students Choose GetCopy

### 📚 Better Grades, Less Stress
- Improve your writing quality with AI-powered suggestions
- Get real-time feedback on grammar, style, and clarity
- Meet deadlines with confidence

### ⏰ Save Precious Time
- Cut research time in half with smart source suggestions
- Generate outlines in seconds
- Format citations automatically

### 💡 Learn As You Write
- Understand complex topics better with simplified explanations
- Learn from writing suggestions and improvements
- Develop stronger academic writing skills

---

## Features That Make Writing Easier

### Smart Research Assistant
- Find relevant academic sources instantly
- Get article summaries and key points
- Save and organize research materials

### Writing Enhancement
- Real-time grammar and style checks
- Vocabulary suggestions
- Clarity improvements
- Plagiarism prevention

### Citation Made Simple
- Automatic citation generation
- Support for all major formats (APA, MLA, Chicago)
- Bibliography organization

### Academic Templates
- Essay structures
- Research paper formats
- Lab report templates
- Thesis outlines

---

## Pricing Plans for Students

### Free Plan
- Basic writing suggestions
- 3 documents per month
- Standard templates
- [Get Started]

### Student Pro - $9.99/month
- Unlimited documents
- Advanced AI assistance
- All templates
- Priority support
- [Start Free Trial]

### Student Team - $19.99/month
- Everything in Pro
- Group collaboration
- Share templates
- Team workspace
- [Start Free Trial]

*Special discount: 20% off with valid student email

---

## What Students Say

> "GetCopy helped me improve my essay grades from B's to A's. The writing suggestions are like having a personal writing tutor." 
> - Sarah J., Psychology Major

> "I used to spend hours formatting citations. Now it takes minutes. This tool is a lifesaver!"
> - Mike T., Engineering Student

> "The research assistant feature helped me find perfect sources for my thesis. Highly recommend!"
> - Emma L., History Major

---

## Get Started in 3 Simple Steps

1. **Sign Up**
   - Create your account with your student email
   - Get instant access to basic features

2. **Choose Your Plan**
   - Select the plan that fits your needs
   - Start with a 14-day free trial

3. **Start Writing**
   - Upload your assignment or start from scratch
   - Let GetCopy guide you to better writing

[Start Your Free Trial Today]

---

## Frequently Asked Questions

**Q: Is GetCopy suitable for all academic subjects?**
A: Yes! GetCopy supports writing across all academic disciplines, from humanities to sciences.

**Q: Does using GetCopy count as cheating?**
A: No. GetCopy is a learning tool that helps improve your writing skills. All work remains your own.

**Q: Can I use GetCopy on my mobile device?**
A: Yes, GetCopy works on all devices through our web app and mobile apps.

**Q: What if I'm not satisfied with GetCopy?**
A: We offer a 30-day money-back guarantee for all paid plans.

---

## Ready to Transform Your Academic Writing?

Join thousands of students who are already writing better papers and saving time with GetCopy.

[Start Your Free Trial] [Watch Demo] [Contact Support]

---

*Terms and conditions apply. Student verification required for discounts.
```

### Question ###

Think step by step:
1. What HTML structure best organizes this content?
Answer: The content should be structured into sections like Hero, Features, Pricing, etc.

2. Which Tailwind components would maximize conversion?
Answer: Components like buttons, cards, and modals can help drive conversions.

3. What interactive elements would engage students?
Answer: Animations, hover effects, and interactive forms can engage students.

4. How should the responsive design adapt to different screens?
Answer: Use responsive classes like `sm:`, `md:`, and `lg:` to adapt the design to different screens.

Answer in a natural, human-like manner, ensuring the response is unbiased and does not rely on stereotypes.

### Output Primer ###

Begin with the complete HTML structure including Tailwind CSS configuration:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>GetCopy - Academic Writing Assistant</title>
    <!-- Tailwind CSS setup -->
```