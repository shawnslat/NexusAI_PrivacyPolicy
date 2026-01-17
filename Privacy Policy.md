<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - Nexus Core Brief</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
            background: linear-gradient(180deg, #0c0a1e 0%, #13102a 50%, #0c0a1e 100%);
            color: #e2e8f0;
            min-height: 100vh;
            line-height: 1.7;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px 80px;
        }
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        .icon {
            width: 64px;
            height: 64px;
            background: rgba(139, 92, 246, 0.2);
            border-radius: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 16px;
            font-size: 32px;
        }
        h1 {
            color: #ffffff;
            font-size: 28px;
            margin-bottom: 8px;
        }
        .subtitle {
            color: #64748b;
            font-size: 14px;
        }
        .intro-box {
            background: #1e1b4b;
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 24px;
        }
        h2 {
            color: #8b5cf6;
            font-size: 16px;
            margin-bottom: 12px;
            margin-top: 32px;
        }
        .section {
            background: #1e1b4b;
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 16px;
        }
        .section p, .section li {
            color: #94a3b8;
            font-size: 14px;
            margin-bottom: 12px;
        }
        .section ul {
            list-style: none;
            padding: 0;
        }
        .section li {
            padding-left: 20px;
            position: relative;
        }
        .section li::before {
            content: "•";
            color: #8b5cf6;
            position: absolute;
            left: 0;
        }
        .warning-box {
            background: #1e1b4b;
            border: 1px solid #f97316;
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 16px;
        }
        .warning-box h2 {
            color: #f97316;
        }
        .contact-box {
            background: rgba(139, 92, 246, 0.1);
            border: 1px solid #8b5cf6;
            border-radius: 12px;
            padding: 20px;
            margin-top: 32px;
        }
        .contact-box h2 {
            color: #8b5cf6;
            margin-top: 0;
            margin-bottom: 8px;
        }
        .contact-box a {
            color: #8b5cf6;
            text-decoration: none;
        }
        .contact-box a:hover {
            text-decoration: underline;
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            color: #64748b;
            font-size: 12px;
        }
        .app-name {
            color: #8b5cf6;
            font-weight: 600;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="icon">🔒</div>
            <h1>Privacy Policy</h1>
            <p class="subtitle">Effective January 2026</p>
        </div>

        <div class="intro-box">
            <p style="color: #e2e8f0; font-size: 15px;">
                <span class="app-name">Nexus Core Brief</span> ("we", "us", "the App") respects your privacy. This app aggregates publicly available data from free sources (GDELT, HouseStockWatcher, FRED, public RSS feeds, etc.).
            </p>
        </div>

        <h2>1. Information We Collect</h2>
        <div class="section">
            <ul>
                <li>We collect minimal data — most information stays on your device.</li>
                <li>Optional push notifications are stored encrypted on your device only.</li>
                <li>Anonymous usage stats (app opens, crashes) may be collected — no personal identifiers.</li>
                <li>We do NOT sell, share, or transmit your data to third-party brokers or advertisers.</li>
            </ul>
        </div>

        <h2>2. Location Data</h2>
        <div class="section">
            <ul>
                <li>We may request optional coarse location (city-level only) for local features (e.g., local news, nearby events).</li>
                <li>Data is processed on-device, never transmitted, shared, or sold to third parties.</li>
                <li>You can disable or manually set location at any time via device settings or in-app ZIP code entry.</li>
                <li>We do not track your movements or location history.</li>
            </ul>
        </div>

        <h2>3. Minimal Data Collection</h2>
        <div class="section">
            <ul>
                <li>No personal data leaves your device unless explicitly shared by you.</li>
                <li>We do not engage in tracking, profiling, or data brokerage.</li>
                <li>Your preferences, settings, and any API keys are stored locally on your device only.</li>
            </ul>
        </div>

        <h2>4. How We Use Information</h2>
        <div class="section">
            <ul>
                <li>Solely to deliver real-time public data and optional alerts.</li>
                <li>No sharing with third parties except as required by law.</li>
            </ul>
        </div>

        <h2>5. AI Chat Feature (BYOK - Bring Your Own Key)</h2>
        <div class="section">
            <p>If you choose to use the optional AI chat feature:</p>
            <ul>
                <li><strong>Your API Key:</strong> You provide your own API key from a third-party AI provider (OpenAI, Anthropic, xAI, Google, or custom endpoint).</li>
                <li><strong>Key Storage:</strong> Your API key is encrypted and stored on your device only.</li>
                <li><strong>Direct Communication:</strong> Your API key is sent directly from your device to your chosen AI provider — we never see, store, or access it.</li>
                <li><strong>Third-Party Processing:</strong> Conversations are processed by your chosen AI provider according to their privacy policy.</li>
                <li><strong>No Server Storage:</strong> We do not operate servers that store or process your conversations.</li>
            </ul>
        </div>

        <h2>6. Third-Party Services & Data Sources</h2>
        <div class="section">
            <p>This app aggregates publicly available data from external sources including:</p>
            <ul>
                <li>GDELT Project (news/events)</li>
                <li>FRED API (Federal Reserve economic data)</li>
                <li>Public RSS feeds (BBC, Reuters, Al Jazeera, NPR, AP News)</li>
                <li>Public congressional disclosure databases</li>
                <li>Public cyber threat intelligence feeds</li>
            </ul>
            <p style="margin-top: 12px;">We do not control these third-party sources and recommend reviewing their respective privacy policies.</p>
        </div>

        <h2>7. Tracking & Advertising</h2>
        <div class="section">
            <ul>
                <li>This app does NOT track you across other companies' apps or websites.</li>
                <li>This app does NOT contain third-party advertising.</li>
                <li>We do NOT use device identifiers for advertising purposes.</li>
            </ul>
        </div>

        <h2>8. Data Security</h2>
        <div class="section">
            <ul>
                <li>Local preferences are encrypted using device secure storage (Keychain/Keystore).</li>
                <li>No data is sold or used for advertising.</li>
            </ul>
        </div>

        <h2>9. Your Rights</h2>
        <div class="section">
            <ul>
                <li>Request deletion or ask questions: <a href="mailto:privacy@nexuscorebrief.app" style="color: #8b5cf6;">privacy@nexuscorebrief.app</a></li>
                <li>We comply with CCPA and GDPR where applicable (minimal data collected).</li>
                <li>Delete all data by uninstalling the app.</li>
            </ul>
        </div>

        <h2>10. Children's Privacy</h2>
        <div class="section">
            <ul>
                <li>Not intended for users under 13.</li>
                <li>We do not knowingly collect information from children.</li>
            </ul>
        </div>

        <h2>11. Changes</h2>
        <div class="section">
            <ul>
                <li>We may update this policy — continued use constitutes acceptance.</li>
                <li>Material changes will be noted in the app.</li>
            </ul>
        </div>

        <div class="contact-box">
            <h2>Contact</h2>
            <p style="color: #94a3b8;">For any privacy-related questions or concerns:</p>
            <p><a href="mailto:privacy@nexuscorebrief.app">privacy@nexuscorebrief.app</a></p>
        </div>

        <div class="footer">
            <p>Last Updated: January 2026</p>
            <p style="margin-top: 8px;">© 2026 Nexus Core Brief. All rights reserved.</p>
        </div>
    </div>
</body>
</html>
