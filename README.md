<style>
  @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700&display=swap');
  
  /* Aggressively override GitHub Pages default themes */
  header, footer, .page-header, .site-header, .project-name {
    display: none !important;
  }
  
  body, html, .wrapper, .container-lg, main, .markdown-body {
    background-color: #fff0f3 !important;
    background-image: radial-gradient(at 0% 0%, hsla(347,100%,88%,1) 0px, transparent 50%),
                      radial-gradient(at 100% 0%, hsla(340,100%,94%,1) 0px, transparent 50%),
                      radial-gradient(at 100% 100%, hsla(330,100%,89%,1) 0px, transparent 50%) !important;
    font-family: 'Outfit', sans-serif !important;
    color: #2b2d42 !important;
    margin: 0 !important;
    padding: 0 !important;
    max-width: 100% !important;
    border: none !important;
  }
  
  .privacy-container {
    max-width: 900px;
    margin: 40px auto !important;
    padding: 0 20px;
    box-sizing: border-box;
  }
  
  .premium-header {
    text-align: center;
    padding: 70px 20px;
    background: rgba(255, 255, 255, 0.65);
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    border-radius: 40px;
    box-shadow: 0 25px 50px rgba(255, 77, 109, 0.08);
    margin-bottom: 60px;
    border: 1px solid rgba(255, 255, 255, 0.9);
  }
  
  .premium-header img {
    width: 140px;
    border-radius: 35px;
    box-shadow: 0 15px 35px rgba(255, 77, 109, 0.25);
    margin-bottom: 25px;
    animation: float 6s ease-in-out infinite;
    transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  }
  
  @keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-12px); }
    100% { transform: translateY(0px); }
  }
  
  .premium-header img:hover {
    transform: translateY(-15px) scale(1.05);
    animation-play-state: paused;
  }
  
  .premium-header h1 {
    font-size: 52px !important;
    font-weight: 800 !important;
    color: #590d22 !important;
    margin: 0 0 12px 0 !important;
    letter-spacing: -1.5px !important;
    border: none !important;
  }
  
  .premium-header p {
    font-size: 18px !important;
    color: #ff4d6d !important;
    font-weight: 700 !important;
    letter-spacing: 2px !important;
    margin: 0 !important;
    text-transform: uppercase;
  }
  
  .section-card {
    background: #ffffff;
    border-radius: 32px;
    padding: 45px;
    margin-bottom: 40px;
    box-shadow: 0 12px 35px rgba(0, 0, 0, 0.02), 0 2px 5px rgba(0,0,0,0.01);
    border: 1px solid rgba(255, 77, 109, 0.06);
    transition: transform 0.4s ease, box-shadow 0.4s ease;
  }
  
  .section-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 20px 45px rgba(255, 77, 109, 0.12);
  }
  
  .section-card h2 {
    font-size: 30px !important;
    font-weight: 800 !important;
    color: #ff4d6d !important;
    margin-top: 0 !important;
    margin-bottom: 30px !important;
    display: flex;
    align-items: center;
    gap: 18px;
    border: none !important;
    letter-spacing: -0.5px;
  }
  
  .section-card h2 span {
    background: #fff0f3;
    padding: 14px;
    border-radius: 20px;
    display: inline-flex;
    color: #ff4d6d;
    font-size: 26px;
    box-shadow: inset 0 2px 4px rgba(255, 255, 255, 1);
  }
  
  .list-item {
    background: #f8f9fa;
    border-radius: 24px;
    padding: 28px;
    margin-bottom: 20px;
    border-left: 6px solid #ff4d6d;
    transition: all 0.3s ease;
    font-size: 17px;
    color: #4a4e69;
    line-height: 1.7;
  }
  
  .list-item:hover {
    background: #fff0f3;
    transform: translateX(5px);
  }
  
  .list-item strong {
    color: #590d22;
    font-size: 20px;
    display: block;
    margin-bottom: 10px;
    font-weight: 700;
  }
  
  .highlight-box {
    background: linear-gradient(135deg, #ff758f 0%, #ff4d6d 100%);
    color: white;
    padding: 35px;
    border-radius: 28px;
    margin-top: 35px;
    box-shadow: 0 20px 40px rgba(255, 77, 109, 0.25);
  }
  
  .highlight-box p {
    color: white !important;
    font-size: 18px !important;
    font-weight: 500;
  }
  
  .primary-btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(135deg, #ff758f 0%, #ff4d6d 100%);
    color: white !important;
    padding: 20px 50px;
    border-radius: 100px;
    font-size: 22px;
    font-weight: 700;
    text-decoration: none !important;
    box-shadow: 0 15px 35px rgba(255, 77, 109, 0.35);
    transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    margin-top: 20px;
    border: 2px solid rgba(255, 255, 255, 0.2);
  }
  
  .primary-btn:hover {
    transform: translateY(-5px) scale(1.03);
    box-shadow: 0 25px 45px rgba(255, 77, 109, 0.45);
    background: linear-gradient(135deg, #ff8fa3 0%, #ff4d6d 100%);
  }
  
  .footer-cta {
    text-align: center;
    margin: 80px 0 40px 0;
  }
</style>

<div class="privacy-container">
  <div class="premium-header">
    <img src="app_icon_ios.png" alt="Basty App Icon" />
    <h1>Privacy Policy</h1>
    <p>EFFECTIVE DATE: SEPTEMBER 12, 2026</p>
  </div>

  <div class="section-card">
    <h2><span>👋</span> 1. Introduction</h2>
    <p style="font-size: 18px; color: #4a4e69; line-height: 1.8;">Welcome to <strong>Basty</strong> ("we," "our," or "us"). We are committed to protecting your personal information and your right to privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our mobile application (the "App"). By downloading, accessing, or using the App, you agree to the collection and use of information in accordance with this Privacy Policy.</p>
  </div>

  <div class="section-card">
    <h2><span>🔍</span> 2. Information We Collect</h2>
    <p style="margin-bottom: 30px; font-size: 18px; color: #4a4e69;">We collect the following types of information to provide and improve our services to you:</p>
    
    <div class="list-item">
      <strong>👤 Personal Identification Information</strong>
      We collect information such as your phone number and email address for account registration, communication, and order processing.
    </div>
    
    <div class="list-item">
      <strong>📍 Location Data</strong>
      We request access to your device's location <em>only while the App is in use</em> (foreground) to determine if you are within our delivery regions and to accurately set your delivery destination for orders. We do not track your location in the background.
    </div>
    
    <div class="list-item">
      <strong>📷 Camera and Photo Gallery</strong>
      We request access to your device's camera and photo gallery to allow you to set a user profile picture and to upload custom images that will be printed on top of your cake orders. <em>Images uploaded for cake printing are only retained for as long as it takes to fulfill your order, after which they are safely deleted.</em>
    </div>
    
    <div class="list-item">
      <strong>📱 Device and Usage Data</strong>
      We collect diagnostic data, crash reports, and app usage analytics (such as device type and operating system) to help us improve app stability and performance.
    </div>
  </div>

  <div class="section-card">
    <h2><span>🛠️</span> 3. How We Use Your Information</h2>
    <p style="margin-bottom: 25px; font-size: 18px; color: #4a4e69;">We use the collected information for various purposes, including:</p>
    <ul style="line-height: 2.2; color: #4a4e69; font-size: 18px; padding-left: 25px;">
      <li>To create and manage your account.</li>
      <li>To process your orders, process payments, and manage deliveries.</li>
      <li>To customize our products based on your requests (e.g., printing uploaded images on cakes).</li>
      <li>To communicate with you regarding your account, orders, and customer support inquiries.</li>
      <li>To monitor app usage, identify bugs, and improve the overall user experience.</li>
      <li>To send you push notifications regarding your order status and important app updates.</li>
    </ul>
  </div>

  <div class="section-card">
    <h2><span>🤝</span> 4. Third-Party Services</h2>
    <p style="margin-bottom: 30px; font-size: 18px; color: #4a4e69;">We <strong>do not</strong> sell, trade, or otherwise transfer your personally identifiable information to outside parties. We only share information with trusted third-party service providers:</p>
    
    <div class="list-item">
      <strong>💳 Payment Processors</strong>
      We use secure third-party payment gateways (including Yussor Pay, MAsrafy Pay, and Sahara Pay) to process your transactions. We do not store your payment card details on our servers.
    </div>
    
    <div class="list-item">
      <strong>📊 Analytics and Infrastructure</strong>
      We use third-party services like Firebase (including Google Analytics and Firebase Crashlytics) for backend infrastructure, push notifications, understanding app usage, and resolving technical issues.
    </div>
    
    <div class="highlight-box">
      <p style="margin: 0; line-height: 1.8;">💡 <strong>Transparency Tip:</strong> We encourage you to review the privacy policies of our third-party service providers (such as Google/Firebase and your selected payment gateway) to understand how they handle your data.</p>
    </div>
  </div>

  <div class="section-card">
    <h2><span>🗑️</span> 5. Data Retention & Deletion</h2>
    <p style="font-size: 18px; color: #4a4e69; line-height: 1.8;">You have the right to request the deletion of your personal data at any time. We provide a convenient <strong>in-app account deletion feature</strong> that allows you to permanently delete your account and associated data directly from the App's settings.</p>
    <p style="font-size: 18px; color: #4a4e69; margin-top: 20px; line-height: 1.8;">Alternatively, you may contact us to request data deletion. We will retain your information only for as long as is necessary for the purposes set out in this Privacy Policy or as required by law.</p>
  </div>

  <div class="section-card">
    <h2><span>🔒</span> 6. Security of Your Data</h2>
    <p style="font-size: 18px; color: #4a4e69;">The security of your data is very important to us. We implement reasonable administrative, technical, and physical security measures to protect your personal information.</p>
    <div class="list-item" style="border-left-color: #2a9d8f; background: #e9f5f4; margin-top: 30px; margin-bottom: 30px;">
      <strong style="color: #21867a;">🔐 Encrypted in Transit</strong>
      All data transmitted between the App and our servers is encrypted in transit using secure connections (HTTPS).
    </div>
    <p style="font-size: 16px; opacity: 0.8; color: #4a4e69; line-height: 1.7;">However, please remember that no method of transmission over the internet or method of electronic storage is 100% secure, and we cannot guarantee its absolute security.</p>
  </div>

  <div class="section-card">
    <h2><span>🔞</span> 7. Age Restriction</h2>
    <p style="font-size: 18px; color: #4a4e69; line-height: 1.8;">Our App is intended for users who are <strong>18 years of age or older</strong>. We do not knowingly collect personally identifiable information from anyone under the age of 18. If you are a parent or guardian and you are aware that your child has provided us with personal data, please contact us. If we become aware that we have collected personal data from children without verification of parental consent, we will take steps to securely remove that information from our servers.</p>
  </div>

  <div class="section-card">
    <h2><span>🔄</span> 8. Changes to Policy</h2>
    <p style="font-size: 18px; color: #4a4e69; line-height: 1.8;">We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top. You are advised to review this Privacy Policy periodically for any changes.</p>
  </div>

  <div class="footer-cta">
    <h2 style="font-size: 36px; color: #590d22; font-weight: 800; margin-bottom: 15px;">Have questions?</h2>
    <p style="font-size: 20px; color: #ff4d6d; font-weight: 500; margin-bottom: 30px;">We're always here to help you out.</p>
    <a href="contact/" class="primary-btn">Contact Support 🚀</a>
  </div>
</div>
