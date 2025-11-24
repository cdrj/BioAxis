# Agents Documentation

## Overview

This document outlines the agent architecture and workflow for the BioAxis joint angle measurement application.

## Purpose

BioAxis Pro V5 is a sophisticated web-based tool for measuring joint angles in photographs. The application provides medical professionals, physical therapists, and sports scientists with an easy-to-use platform for biomechanical analysis.

## Key Features

### Image Upload & Processing
- Drag-and-drop interface for image upload
- Support for JPG, PNG high-resolution images
- Automatic canvas adaptation to image dimensions
- Zoom controls for precise measurements

### Measurement Modes
1. **Normal Mode**: 3-point angle measurement
   - Select three points to measure joint angles
   - Visual angle sector display
   - Automatic degree calculation

2. **Horizontal Mode**: Baseline horizontal reference
   - 2-point measurement with horizontal reference line
   - Useful for measuring joint flexion/extension angles

3. **Vertical Mode**: Baseline vertical reference
   - 2-point measurement with vertical reference line
   - Ideal for measuring abduction/adduction angles

### UI/UX Features
- Dark/Light mode toggle
- Responsive design for mobile devices
- iOS Safari optimization with safe area support
- Touch-friendly interface with 44px minimum touch targets
- Undo/Clear functionality
- Real-time angle display with professional typography

## Technical Architecture

### Frontend Stack
- **HTML5**: Semantic structure
- **CSS3**: Modern styling with CSS variables for theming
- **Vanilla JavaScript**: Core functionality without framework dependencies
- **Canvas API**: Image rendering and measurement visualization

### Mobile Optimization
- Viewport configuration for mobile devices
- Safe area inset handling for modern iOS devices
- Touch event handling with proper passive/active flags
- Responsive layout adaptation

### Accessibility Features
- WCAG 2.1 compliant color contrast ratios
- Keyboard navigation support
- Screen reader friendly markup
- Proper touch target sizes (minimum 44px)

## File Structure

```
fitness-tool/
├── index.html          # Main application file
├── agents.md          # This documentation
└── README.md          # Project documentation
```

## Browser Compatibility

### Desktop
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Mobile
- iOS Safari 14+
- Chrome Mobile 90+
- Samsung Internet 15+

## Performance Considerations

- Optimized canvas rendering
- Efficient touch event handling
- Minimal external dependencies
- Fast image loading and processing

## Security Notes

- No external API calls
- Client-side image processing only
- No data transmission to external servers
- Local storage optimization

## Future Enhancements

### Planned Features
- Measurement history and export functionality
- Multiple measurement overlay support
- Calibration tools for accurate measurements
- DICOM format support
- Integration with medical record systems

### Technical Improvements
- Progressive Web App (PWA) capabilities
- Offline functionality
- Enhanced keyboard shortcuts
- Batch image processing
- Video frame analysis

## Contributing Guidelines

When contributing to this project:

1. Ensure mobile-first responsive design
2. Test across iOS and Android devices
3. Maintain accessibility standards
4. Follow the existing code structure
5. Test with various image formats and sizes

## Support

For technical support or feature requests, please refer to the project repository issues section.