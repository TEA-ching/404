# 404 - Lost in Translation

A creative 404 error page featuring the word "lost" translated into 130+ languages, displayed in a visually appealing word cloud format.

## Features

- **Multilingual**: Contains "lost" translated into over 130 different languages
- **Responsive Design**: Adapts to all screen sizes (landscape and portrait)
- **Full Screen**: Always fills the entire viewport
- **Centered Focus**: The word "lost" remains centered at all times
- **Random Layout**: If JavaScript is enabled, the translations are randomly repositioned on each page load
- **Pure CSS**: No external dependencies required
- **SVG-based**: Scalable vector graphics for crisp rendering at any size

## Technical Details

- **Format**: 16:9 aspect ratio (1920x1080 viewBox)
- **Styling**: Pure CSS with flexbox centering
- **Languages**: 130+ unique translations from various language families
- **Font**: Arial/Helvetica sans-serif
- **Colors**: White for "lost", various shades of gray for translations

## Usage

Simply open `index.html` in any modern web browser. The page works without any server or build process.

```bash
# Open directly in browser
open index.html
```

Or serve it with any static web server:

```bash
# Python 3
python -m http.server 8000

# Node.js (http-server)
npx http-server
```

## Customization

You can customize:
- **Colors**: Modify the `fill` attributes in the SVG text elements
- **Fonts**: Change the `font-family` in the SVG style section
- **Background**: Adjust the `background-color` in the CSS
- **Translations**: Add or modify words in the SVG

## Deployment

### Automatic Deployment with GitHub Actions

This repository includes a GitHub Actions workflow that automatically:
1. Creates a ZIP file containing `index.html`
2. Publishes it as a release named "last"
3. Updates the release on every push to main/master branch

The workflow runs automatically on each push and creates a downloadable ZIP perfect for deploying to Cloudflare Pages or any static hosting service.

### Deploy to Cloudflare Pages

You can deploy this 404 page to Cloudflare Pages in several ways:

#### Option 1: Direct Upload (Recommended)
1. Download the latest release: [404-page.zip](../../releases/latest/download/404-page.zip)
2. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
3. Create a new project
4. Upload the ZIP file directly
5. Configure your custom 404 page in Cloudflare settings

#### Option 2: GitHub Integration
1. Connect your GitHub repository to Cloudflare Pages
2. Configure build settings:
   - Build command: `echo "No build needed"`
   - Build output directory: `/`
3. Deploy automatically on each push

#### Option 3: Wrangler CLI
```bash
# Install Wrangler
npm install -g wrangler

# Deploy
wrangler pages deploy . --project-name=404-lost-in-translation
```

### Deploy to Other Platforms

The `index.html` file is completely self-contained and can be deployed to:
- **Netlify**: Drag and drop the ZIP or connect via Git
- **Vercel**: Import the repository or use `vercel` CLI
- **GitHub Pages**: Enable in repository settings
- **Any static hosting**: Upload the HTML file

## Browser Support

Works in all modern browsers that support:
- CSS Flexbox
- SVG
- ES6 JavaScript (for random shuffling)

Gracefully degrades if JavaScript is disabled - translations remain in their original positions.

## License

MIT License - see [LICENSE.md](LICENSE.md) for details.

## Author

**Ronan Le Meillat** - SCTG Development

© 2025 All rights reserved.

## Contributing

Feel free to submit issues or pull requests if you'd like to add more translations or improve the design!

## Complete List of Translations

The page features "lost" translated into 131 languages:

1. **lost** - English
2. **perdu** - French
3. **kadonnut** - Finnish
4. **verloren** - German/Dutch
5. **потерянный** - Russian
6. **失われた** - Japanese
7. **สูญหาย** - Thai
8. **丢失** - Chinese (Simplified)
9. **잃어버린** - Korean
10. **فقد** - Arabic
11. **אבד** - Hebrew
12. **χαμένος** - Greek
13. **förlorade** - Swedish
14. **tapt** - Norwegian
15. **tabt** - Danish
16. **galduta** - Basque
17. **elveszett** - Hungarian
18. **missed** - English
19. **изгубен** - Macedonian
20. **खो गया** - Hindi
21. **शेर हो गया** - Hindi
22. **stracony** - Polish
23. **borta** - Swedish
24. **kayboldu** - Turkish
25. **tévedt** - Hungarian
26. **vermisst** - German
27. **perdido** - Spanish/Portuguese
28. **felizg** - Unknown
29. **disperso** - Italian/Spanish
30. **ztracený** - Czech
31. **kadonnud** - Estonian
32. **perdut** - Catalan
33. **загублений** - Ukrainian
34. **pierdut** - Romanian
35. **tapita** - Swahili
36. **zudis** - Latvian
37. **paveldėti** - Lithuanian
38. **사라진** - Korean
39. **失った** - Japanese
40. **hilang** - Malay/Indonesian
41. **tappato** - Maltese
42. **നഷ്ടപ്പെട്ടു** - Malayalam
43. **пропавший** - Russian
44. **消失した** - Japanese
45. **desaparecido** - Spanish/Portuguese
46. **消えた** - Japanese
47. **spărit** - Romanian
48. **пропащий** - Russian
49. **zagubiony** - Polish
50. **zablúdený** - Slovak
51. **extraviado** - Spanish
52. **kayıp** - Turkish
53. **perduto** - Italian
54. **izmidzis** - Latvian
55. **пропаднал** - Bulgarian
56. **დაკარგული** - Georgian
57. **կորած** - Armenian
58. **жоғалған** - Kazakh
59. **verlore** - Afrikaans
60. **caduto** - Italian
61. **difuminat** - Romanian
62. **faillí** - Irish
63. **hävinnyt** - Finnish
64. **perdida** - Spanish/Portuguese (feminine)
65. **izgubljen** - Serbian/Croatian
66. **απολεσθέν** - Greek (ancient)
67. **তলাশা** - Bengali
68. **perso** - Italian
69. **χαμένο** - Greek
70. **ضاع** - Arabic
71. **kaybolmuş** - Turkish
72. **失われる** - Japanese
73. **שאבד** - Hebrew
74. **förlust** - Swedish
75. **kaybetti** - Turkish
76. **caillte** - Irish
77. **smarrito** - Italian
78. **kadonneena** - Finnish
79. **rătăcit** - Romanian
80. **desaparegut** - Catalan
81. **загубљен** - Serbian (Cyrillic)
82. **жоғалды** - Kazakh
83. **անհետացել** - Armenian
84. **হারিয়ে** - Bengali
85. **утерянный** - Russian
86. **行方不明** - Japanese
87. **stratený** - Slovak
88. **ausente** - Spanish/Portuguese
89. **исчезнувший** - Russian
90. **elhagyott** - Hungarian
91. **rozptýlený** - Czech
92. **ztratil** - Czech
93. **katonut** - Finnish
94. **desapareguda** - Catalan (feminine)
95. **втрачений** - Ukrainian
96. **dispărut** - Romanian
97. **umepotea** - Swahili
98. **pazudis** - Latvian
99. **dingo** - Lithuanian
100. **길잃은** - Korean
101. **紛失** - Japanese
102. **kehilangan** - Indonesian/Malay
103. **mitiet** - Latvian
104. **extraño** - Spanish
105. **נעלם** - Hebrew
106. **затерянный** - Russian
107. **desvanecido** - Spanish
108. **kaybolan** - Turkish
109. **verschwunden** - German
110. **sparito** - Italian
111. **消逝** - Chinese
112. **norimet** - Unknown
113. **égaré** - French
114. **eltűnt** - Hungarian
115. **消える** - Japanese
116. **zaginiony** - Polish
117. **пропал** - Russian
118. **absens** - Latin
119. **ضائع** - Arabic
120. **zâmbit** - Romanian
121. **пропало** - Russian
122. **കളഞ്ഞു** - Malayalam
123. **dingęs** - Lithuanian
124. **försvunnen** - Swedish
125. **егарь** - Belarusian
126. **изчезнал** - Bulgarian
127. **સ્વાહા** - Gujarati

*Note: Some translations may have multiple variants or regional differences. Language identification is approximate for some words.*

