## Creative-Level Framework FAQ

### Introduction to AudienceLab’s Creative-Level Framework

AudienceLab’s creative-level framework is designed to address the needs of modern digital advertising, navigating through strict privacy regulations while delivering precise and actionable advertising analytics. This approach replaces traditional user-level tracking with a system that focuses solely on ad creatives, ensuring compliance and enhancing ad performance insights without infringing on user privacy.

### How Does the Creative-Level Framework Work?

#### 1. **Integration of AudienceLab SDK**:

- Mobile game developers integrate the AudienceLab SDK into apps and games. This SDK establishes a direct connection between the game and selected advertising networks, facilitating the exchange of data exclusively at the creative level.

#### 2. **Unique Tracking Schema**:

- This system is designed to accurately trace the origin of user sessions only to the specific creatives they interact with.
- More about this in the Unique Tracking Schema section below.

#### 3. **Collection of Incremental Performance Metrics**:

- The SDK methodically collects and aggregates incremental performance metrics based on the creatives that directed users to the app. This data provides a detailed view of how each ad creative contributes to user acquisition and engagement, allowing for precise analysis and optimization without compromising privacy.

#### 4. **Collaboration with Self-Attributing Networks**:

- We also support integration with self-attributing networks that utilize their proprietary, web-based attribution models. These models function independently of SKAN and other user-level frameworks, aligning perfectly with our creative-level tracking.

### Benefits of the Creative-Level Framework

#### 1. **Enhanced User Privacy**:

- AudienceLab’s framework is meticulously designed to be privacy-centric, completely bypassing the items in Apple’s “Required Reasons” API. Therefore, it does not necessitate mention in the privacy manifest of apps, offering a seamless user experience devoid of privacy intrusions.

#### 2. **Accurate and Timely Insights**:

- Unlike traditional methods that may suffer from delays or restrictions in data access, our framework provides real-time insights into the performance of ad creatives. Marketers can quickly adapt and optimize their strategies based on current and comprehensive data.

#### 3. **Improved Fraud Detection**:

- With detailed tracking at the creative level, our system can more effectively identify irregular patterns that may indicate fraudulent activities, such as bot interactions or skewed engagement metrics.

#### 4. **Scalability and Flexibility**:

- The platform not only supports expansive campaign scales but also offers extensive customization in tracking configurations. This flexibility ensures that advertisers can tailor their strategies to meet diverse campaign requirements while upholding stringent privacy standards.

### Unique Tracking Schema Overview

AudienceLab employs a sophisticated creative-level tracking system set up directly on the ad networks. This system is designed to accurately trace the origin of user sessions to the specific creatives they interact with, facilitating precise data collection without involving personal user data.

### Key Components of the Tracking Schema

#### 1. **Creative-Level Tracking**:

- The tracking system identifies the specific ad creative that directed a user to the app. By associating user sessions with ad creatives rather than personal identifiers, the system ensures anonymity and compliance with stringent privacy regulations.

#### 2. **Use of Deferred Deep Linking**:

- As part of our toolkit, we utilize deferred deep linking technology. This allows the SDK to not only recognize the user’s entry point but also maintain this context through the installation process. Once the app is launched for the first time, the SDK retrieves the specific creative information, effectively attributing the session to the correct ad creative even if the user installs the app at a later time.

### Conclusion

Our unique tracking schema, enhanced by tools like deferred deep linking, sets a new standard in creative-level tracking by accurately attributing user sessions to specific ad creatives. This approach not only respects user privacy by avoiding personal data collection but also provides marketers with precise tools for campaign assessment and optimization in a privacy-focused advertising landscape.
