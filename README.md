<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Our Wi-Fi Network</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            color: #333;
        }

        p {
            line-height: 1.6;
        }

        ol,
        ul {
            margin-left: 20px;
        }

        #hindiMessage {
            display: none;
        }

        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-bottom: 20px;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>

<body>
    <button onclick="toggleLanguage()" id="toggleButton">Toggle Language (English)</button>

    <h1>Welcome to Our Wi-Fi Network!</h1>

    <div id="englishMessage">
        <p>Thank you for connecting to our network. Before proceeding, please read the following guidelines for a safe and enjoyable experience:</p>

        <ol>
            <li><strong>Usage Caution:</strong> This network is for authorized use only. Please refrain from any unauthorized access or activities.</li>
            <li><strong>Bandwidth Consideration:</strong> Be mindful of your internet usage to ensure a smooth experience for all users on the network.</li>
            <li><strong>Security First:</strong> Protect your devices with up-to-date antivirus and security software. Avoid sharing sensitive information over the network.</li>
            <li><strong>No Illegal Activities:</strong> Engaging in illegal activities or violating terms of service is strictly prohibited.</li>
            <li><strong>Consent to Monitoring:</strong> By connecting to this network, you consent to the monitoring of your network usage for security and performance purposes.</li>
            <li><strong>Guest Network:</strong> If available, consider using the designated guest network for visitors.</li>
            <li><strong>Technical Support:</strong> For any technical issues or assistance, please contact [Your Contact Information].</li>
        </ol>

        <p>Enjoy your time on our network responsibly!</p>
    </div>

    <div id="hindiMessage">
        <p>हमारे नेटवर्क से जुड़ने के लिए धन्यवाद। आगे बढ़ने से पहले, कृपया एक सुरक्षित और आनंदमय अनुभव के लिए निम्नलिखित दिशा-निर्देशों को पढ़ें:</p>

        <ol>
            <li><strong>उपयोग सावधानी:</strong> यह नेटवर्क केवल अधिकृत उपयोग के लिए है। कृपया अनधिकृत पहुंच या गतिविधियों से बचें।</li>
            <li><strong>बैंडविड्थ का ध्यान रखें:</strong> आपके इंटरनेट उपयोग को सुनिश्चित करें ताकि नेटवर्क के सभी उपयोगकर्ताओं के लिए सहज अनुभव हो।</li>
            <li><strong>सुरक्षा पहले:</strong> अपने डिवाइस को आधुनिक एंटीवायरस और सुरक्षा सॉफ़्टवेयर से सुरक्षित रखें। कृपया नेटवर्क पर संवेदनशील जानकारी साझा न करें।</li>
            <li><strong>अवैध गतिविधियों से बचें:</strong> अवैध गतिविधियों में शामिल होना या सेवा की शर्तों का उल्लंघन करना सख्त रूप से निषिद्ध है।</li>
            <li><strong>मॉनिटरिंग के लिए सहमति:</strong> इस नेटवर्क से जुड़ने के साथ, आप मॉनिटरिंग के लिए अपनी नेटवर्क उपयोग की सहमति देते हैं, सुरक्षा और प्रदर्शन उद्देश्यों के लिए।</li>
            <li><strong>अतिथि नेटवर्क:</strong> यदि उपलब्ध हो, आगंतुकों के लिए निर्धारित अतिथि नेटवर्क का उपयोग करें।</li>
            <li><strong>तकनीकी सहायता:</strong> किसी भी तकनीकी समस्या या सहायता के लिए, कृपया [आपका संपर्क जानकारी] से संपर्क करें।</li>
        </ol>

        <p>हमारे नेटवर्क पर जिम्मेदारीपूर्वक समय बिताएं!</p>
    </div>

    <script>
        function toggleLanguage() {
            var englishMessage = document.getElementById("englishMessage");
            var hindiMessage = document.getElementById("hindiMessage");
            var toggleButton = document.getElementById("toggleButton");

            if (englishMessage.style.display === "none") {
                englishMessage.style.display = "block";
                hindiMessage.style.display = "none";
                toggleButton.innerText = "Toggle Language (English)";
            } else {
                englishMessage.style.display = "none";
                hindiMessage.style.display = "block";
                toggleButton.innerText = "Toggle Language (Hindi)";
            }
        }
    </script>
</body>

</html>
