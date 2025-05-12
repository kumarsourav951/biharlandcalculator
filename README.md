# Advance Land Calculator

A comprehensive Android application for land measurement conversions, specifically designed for traditional and modern land units used in various districts of India.

## Features

### 1. Land Unit Conversion
- **Traditional Units**
  - Bigha
  - Kattha
  - Dhur
  - Dhurki
- **Modern Units**
  - Acres
  - Dismil
  - Square Feet
  - Square Meters

### 2. District-Specific Calculations
- Support for multiple districts with accurate measurements
- Each district has its own laghi (हाथ) value
- Automatic conversion based on district-specific measurements
- Request new district addition with custom laghi values

### 3. Map Scale Conversion
- Convert between map and ground measurements
- Support for multiple scales:
  - 16" = 1 mile
  - 32" = 1 mile
  - 64" = 1 mile
- Convert कड़ी (map) to फिट (ground) and vice versa

### 4. Custom Unit Support
- Create custom laghi values
- Save and reuse custom measurements
- Perfect for unique local measurements

### 5. Admin Features
- District management
- Request approval system
- Ad management
- User statistics

## Technical Details

### Prerequisites
- Android Studio Arctic Fox or newer
- Minimum SDK: API 21 (Android 5.0)
- Target SDK: API 34 (Android 14)
- Gradle version: 7.0.0 or higher

### Dependencies
```gradle
dependencies {
    implementation 'androidx.appcompat:appcompat:1.6.1'
    implementation 'com.google.android.material:material:1.11.0'
    implementation 'com.google.firebase:firebase-database:20.3.0'
    implementation 'com.google.android.gms:play-services-ads:22.6.0'
}
```

### Firebase Integration
- Real-time database for district data
- User statistics tracking
- Admin authentication
- Ad management

### Architecture
- Activity-based architecture
- Firebase Realtime Database
- Material Design components
- Responsive UI with dark mode support

## User Guide

### Basic Conversion
1. Select your district
2. Enter values in any unit
3. Click convert to see results
4. Toggle between traditional and modern units

### Map Scale Conversion
1. Select map scale
2. Enter कड़ी (map) or फिट (ground) value
3. Get instant conversion

### Requesting New District
1. Open navigation drawer
2. Select "Request District"
3. Enter district name and laghi value
4. Add optional notes
5. Submit request

### Custom Unit
1. Open navigation drawer
2. Select "Custom Unit"
3. Enter laghi value
4. Save and use

## Admin Guide

### Accessing Admin Panel
1. Open navigation drawer
2. Select "Admin"
3. Enter credentials

### Managing Districts
- Add new districts
- Delete existing districts
- Update laghi values
- Review and approve requests

### Managing Ads
- Enable/disable ads
- Update AdMob App ID
- Monitor ad performance

## Security

### Admin Security
- Password-protected admin panel
- Firebase authentication
- Secure credential storage

### Data Security
- Firebase security rules
- Data validation
- Input sanitization

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Contact

For support or queries, please contact:
- Email: [Your Email]
- Website: [Your Website]

## Acknowledgments

- Material Design for UI components
- Firebase for backend services
- AdMob for monetization
- All contributors and users

## Version History

### v1.0.0
- Initial release
- Basic conversion features
- District management
- Admin panel

### v1.1.0
- Added map scale conversion
- Improved UI/UX
- Added notes in district requests
- Enhanced admin features

## Future Plans

- [ ] Add more traditional units
- [ ] Support for more regions
- [ ] Offline mode
- [ ] Export/Import functionality
- [ ] Multi-language support 