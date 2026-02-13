<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kaizen Idea Submission</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .container {
            background: white;
            border-radius: 16px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            max-width: 600px;
            width: 100%;
            padding: 40px;
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .header h1 {
            color: #333;
            font-size: 28px;
            margin-bottom: 8px;
        }

        .header p {
            color: #666;
            font-size: 14px;
        }

        .form-group {
            margin-bottom: 24px;
        }

        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
            font-weight: 500;
            font-size: 14px;
        }

        input[type="text"],
        input[type="email"],
        select,
        textarea {
            width: 100%;
            padding: 12px 16px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 14px;
            transition: border-color 0.3s;
            font-family: inherit;
        }

        input[type="text"]:focus,
        input[type="email"]:focus,
        select:focus,
        textarea:focus {
            outline: none;
            border-color: #667eea;
        }

        textarea {
            resize: vertical;
            min-height: 120px;
        }

        select {
            cursor: pointer;
            background-color: white;
        }

        .submit-btn {
            width: 100%;
            padding: 14px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .submit-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(102, 126, 234, 0.4);
        }

        .submit-btn:active {
            transform: translateY(0);
        }

        .submit-btn:disabled {
            background: #ccc;
            cursor: not-allowed;
            transform: none;
        }

        .message {
            padding: 12px 16px;
            border-radius: 8px;
            margin-bottom: 20px;
            display: none;
            font-size: 14px;
        }

        .message.success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }

        .message.error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }

        .required {
            color: #e74c3c;
        }

        .loading {
            display: none;
            text-align: center;
            margin-top: 10px;
        }

        .loading.active {
            display: block;
        }

        .spinner {
            border: 3px solid #f3f3f3;
            border-top: 3px solid #667eea;
            border-radius: 50%;
            width: 30px;
            height: 30px;
            animation: spin 1s linear infinite;
            margin: 0 auto;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .language-toggle {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-bottom: 30px;
        }

        .lang-btn {
            padding: 10px 24px;
            border: 2px solid #667eea;
            background: white;
            color: #667eea;
            border-radius: 8px;
            font-size: 14px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }

        .lang-btn.active {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .lang-btn:hover {
            transform: translateY(-2px);
        }

        .optional-field {
            display: none;
        }

        .optional-field.show {
            display: block;
        }

        .yes-no-toggle {
            display: flex;
            gap: 10px;
            margin-top: 8px;
        }

        .toggle-btn {
            padding: 8px 20px;
            border: 2px solid #e0e0e0;
            background: white;
            border-radius: 6px;
            cursor: pointer;
            font-size: 14px;
            transition: all 0.3s;
        }

        .toggle-btn.active {
            border-color: #667eea;
            background: #667eea;
            color: white;
        }

        .toggle-btn:hover {
            border-color: #667eea;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1 id="mainTitle">💡 Kaizen Idea Submission</h1>
            <p id="subtitle">Share your continuous improvement ideas</p>
        </div>

        <div class="language-toggle">
            <button type="button" class="lang-btn active" onclick="setLanguage('en')" id="btnEnglish">English</button>
            <button type="button" class="lang-btn" onclick="setLanguage('hi')" id="btnHindi">हिंदी</button>
        </div>

        <div id="message" class="message"></div>

        <form id="kaizenForm">
            <div class="form-group">
                <label for="name" id="lblName">Full Name <span class="required">*</span></label>
                <input type="text" id="name" name="name" required placeholder="Enter your full name">
            </div>

            <div class="form-group">
                <label id="lblProvideEmail">Do you want to provide your email?</label>
                <div class="yes-no-toggle">
                    <button type="button" class="toggle-btn" onclick="toggleOptionalField('email', true)" id="btnEmailYes">Yes</button>
                    <button type="button" class="toggle-btn active" onclick="toggleOptionalField('email', false)" id="btnEmailNo">No</button>
                </div>
            </div>

            <div class="form-group optional-field" id="emailField">
                <label for="email" id="lblEmail">Email</label>
                <input type="email" id="email" name="email" placeholder="your.email@company.com">
            </div>

            <div class="form-group">
                <label id="lblProvideEmpId">Do you want to provide your Employee ID?</label>
                <div class="yes-no-toggle">
                    <button type="button" class="toggle-btn" onclick="toggleOptionalField('employeeId', true)" id="btnEmpIdYes">Yes</button>
                    <button type="button" class="toggle-btn active" onclick="toggleOptionalField('employeeId', false)" id="btnEmpIdNo">No</button>
                </div>
            </div>

            <div class="form-group optional-field" id="employeeIdField">
                <label for="employeeId" id="lblEmployeeId">Employee ID</label>
                <input type="text" id="employeeId" name="employeeId" placeholder="Enter your employee ID">
            </div>

            <div class="form-group">
                <label for="department" id="lblDepartment">Department <span class="required">*</span></label>
                <select id="department" name="department" required>
                    <option value="">Select your department</option>
                    <option value="Production">Production</option>
                    <option value="Quality">Quality</option>
                    <option value="Maintenance">Maintenance</option>
                    <option value="Engineering">Engineering</option>
                    <option value="HR">HR</option>
                    <option value="Finance">Finance</option>
                    <option value="IT">IT</option>
                    <option value="Sales & Marketing">Sales & Marketing</option>
                    <option value="Logistics">Logistics</option>
                    <option value="Administration">Administration</option>
                    <option value="Other">Other</option>
                </select>
            </div>

            <div class="form-group">
                <label for="kaizenIdea" id="lblKaizenIdea">Kaizen Idea <span class="required">*</span></label>
                <textarea id="kaizenIdea" name="kaizenIdea" required placeholder="Describe your improvement idea in detail..."></textarea>
            </div>

            <div class="form-group">
                <label for="category" id="lblCategory">Category</label>
                <select id="category" name="category">
                    <option value="">Select category (optional)</option>
                    <option value="Cost Reduction">Cost Reduction</option>
                    <option value="Quality Improvement">Quality Improvement</option>
                    <option value="Safety">Safety</option>
                    <option value="Productivity">Productivity</option>
                    <option value="Environmental">Environmental</option>
                    <option value="Workplace Organization">Workplace Organization</option>
                    <option value="Process Improvement">Process Improvement</option>
                </select>
            </div>

            <button type="submit" class="submit-btn" id="submitBtn">Submit Idea</button>
            
            <div class="loading" id="loading">
                <div class="spinner"></div>
                <p style="margin-top: 10px; color: #666;">Submitting...</p>
            </div>
        </form>
    </div>

    <script>
        const GOOGLE_SCRIPT_URL = 'https://script.google.com/macros/s/AKfycby6Pd9UKqp1QepIvI7yNUB-yuqThz1_WvkwcilsbZMis0cHivtpZVdmPemJSeRaQm3a9g/exec';

        const form = document.getElementById('kaizenForm');
        const submitBtn = document.getElementById('submitBtn');
        const loading = document.getElementById('loading');
        const message = document.getElementById('message');

        let currentLanguage = 'en';

        // Language translations
        const translations = {
            en: {
                mainTitle: '💡 Kaizen Idea Submission',
                subtitle: 'Share your continuous improvement ideas',
                lblName: 'Full Name',
                namePlaceholder: 'Enter your full name',
                lblProvideEmail: 'Do you want to provide your email?',
                lblEmail: 'Email',
                emailPlaceholder: 'your.email@company.com',
                lblProvideEmpId: 'Do you want to provide your Employee ID?',
                lblEmployeeId: 'Employee ID',
                empIdPlaceholder: 'Enter your employee ID',
                lblDepartment: 'Department',
                deptPlaceholder: 'Select your department',
                lblKaizenIdea: 'Kaizen Idea',
                ideaPlaceholder: 'Describe your improvement idea in detail...',
                lblCategory: 'Category',
                categoryPlaceholder: 'Select category (optional)',
                btnYes: 'Yes',
                btnNo: 'No',
                submitBtn: 'Submit Idea',
                submitting: 'Submitting...',
                successMsg: 'Success! Your Kaizen idea has been submitted.',
                errorMsg: 'There was an error submitting your idea. Please try again.',
                departments: {
                    select: 'Select your department',
                    production: 'Production',
                    quality: 'Quality',
                    maintenance: 'Maintenance',
                    engineering: 'Engineering',
                    hr: 'HR',
                    finance: 'Finance',
                    it: 'IT',
                    sales: 'Sales & Marketing',
                    logistics: 'Logistics',
                    administration: 'Administration',
                    other: 'Other'
                },
                categories: {
                    select: 'Select category (optional)',
                    cost: 'Cost Reduction',
                    quality: 'Quality Improvement',
                    safety: 'Safety',
                    productivity: 'Productivity',
                    environmental: 'Environmental',
                    workplace: 'Workplace Organization',
                    process: 'Process Improvement'
                }
            },
            hi: {
                mainTitle: '💡 काइज़न विचार सबमिशन',
                subtitle: 'अपने निरंतर सुधार विचार साझा करें',
                lblName: 'पूरा नाम',
                namePlaceholder: 'अपना पूरा नाम दर्ज करें',
                lblProvideEmail: 'क्या आप अपना ईमेल प्रदान करना चाहते हैं?',
                lblEmail: 'ईमेल',
                emailPlaceholder: 'आपका.ईमेल@कंपनी.com',
                lblProvideEmpId: 'क्या आप अपनी कर्मचारी आईडी प्रदान करना चाहते हैं?',
                lblEmployeeId: 'कर्मचारी आईडी',
                empIdPlaceholder: 'अपनी कर्मचारी आईडी दर्ज करें',
                lblDepartment: 'विभाग',
                deptPlaceholder: 'अपना विभाग चुनें',
                lblKaizenIdea: 'काइज़न विचार',
                ideaPlaceholder: 'अपने सुधार विचार का विस्तार से वर्णन करें...',
                lblCategory: 'श्रेणी',
                categoryPlaceholder: 'श्रेणी चुनें (वैकल्पिक)',
                btnYes: 'हाँ',
                btnNo: 'नहीं',
                submitBtn: 'विचार जमा करें',
                submitting: 'जमा किया जा रहा है...',
                successMsg: 'सफलता! आपका काइज़न विचार सबमिट कर दिया गया है।',
                errorMsg: 'आपका विचार सबमिट करने में त्रुटि हुई। कृपया पुनः प्रयास करें।',
                departments: {
                    select: 'अपना विभाग चुनें',
                    production: 'उत्पादन',
                    quality: 'गुणवत्ता',
                    maintenance: 'रखरखाव',
                    engineering: 'इंजीनियरिंग',
                    hr: 'मानव संसाधन',
                    finance: 'वित्त',
                    it: 'आईटी',
                    sales: 'बिक्री और विपणन',
                    logistics: 'रसद',
                    administration: 'प्रशासन',
                    other: 'अन्य'
                },
                categories: {
                    select: 'श्रेणी चुनें (वैकल्पिक)',
                    cost: 'लागत में कमी',
                    quality: 'गुणवत्ता सुधार',
                    safety: 'सुरक्षा',
                    productivity: 'उत्पादकता',
                    environmental: 'पर्यावरण',
                    workplace: 'कार्यस्थल संगठन',
                    process: 'प्रक्रिया सुधार'
                }
            }
        };

        function setLanguage(lang) {
            currentLanguage = lang;
            const t = translations[lang];

            // Update button states
            document.getElementById('btnEnglish').classList.toggle('active', lang === 'en');
            document.getElementById('btnHindi').classList.toggle('active', lang === 'hi');

            // Update text content
            document.getElementById('mainTitle').textContent = t.mainTitle;
            document.getElementById('subtitle').textContent = t.subtitle;
            document.getElementById('lblName').innerHTML = t.lblName + ' <span class="required">*</span>';
            document.getElementById('name').placeholder = t.namePlaceholder;
            document.getElementById('lblProvideEmail').textContent = t.lblProvideEmail;
            document.getElementById('lblEmail').textContent = t.lblEmail;
            document.getElementById('email').placeholder = t.emailPlaceholder;
            document.getElementById('lblProvideEmpId').textContent = t.lblProvideEmpId;
            document.getElementById('lblEmployeeId').textContent = t.lblEmployeeId;
            document.getElementById('employeeId').placeholder = t.empIdPlaceholder;
            document.getElementById('lblDepartment').innerHTML = t.lblDepartment + ' <span class="required">*</span>';
            document.getElementById('lblKaizenIdea').innerHTML = t.lblKaizenIdea + ' <span class="required">*</span>';
            document.getElementById('kaizenIdea').placeholder = t.ideaPlaceholder;
            document.getElementById('lblCategory').textContent = t.lblCategory;
            document.getElementById('submitBtn').textContent = t.submitBtn;

            // Update Yes/No buttons
            document.getElementById('btnEmailYes').textContent = t.btnYes;
            document.getElementById('btnEmailNo').textContent = t.btnNo;
            document.getElementById('btnEmpIdYes').textContent = t.btnYes;
            document.getElementById('btnEmpIdNo').textContent = t.btnNo;

            // Update department dropdown
            const deptSelect = document.getElementById('department');
            deptSelect.options[0].text = t.departments.select;
            deptSelect.options[1].text = t.departments.production;
            deptSelect.options[2].text = t.departments.quality;
            deptSelect.options[3].text = t.departments.maintenance;
            deptSelect.options[4].text = t.departments.engineering;
            deptSelect.options[5].text = t.departments.hr;
            deptSelect.options[6].text = t.departments.finance;
            deptSelect.options[7].text = t.departments.it;
            deptSelect.options[8].text = t.departments.sales;
            deptSelect.options[9].text = t.departments.logistics;
            deptSelect.options[10].text = t.departments.administration;
            deptSelect.options[11].text = t.departments.other;

            // Update category dropdown
            const catSelect = document.getElementById('category');
            catSelect.options[0].text = t.categories.select;
            catSelect.options[1].text = t.categories.cost;
            catSelect.options[2].text = t.categories.quality;
            catSelect.options[3].text = t.categories.safety;
            catSelect.options[4].text = t.categories.productivity;
            catSelect.options[5].text = t.categories.environmental;
            catSelect.options[6].text = t.categories.workplace;
            catSelect.options[7].text = t.categories.process;

            // Update loading text
            const loadingText = document.querySelector('#loading p');
            if (loadingText) {
                loadingText.textContent = t.submitting;
            }
        }

        function toggleOptionalField(fieldName, show) {
            const field = document.getElementById(fieldName + 'Field');
            const input = document.getElementById(fieldName);
            
            if (show) {
                field.classList.add('show');
                // Update button states
                if (fieldName === 'email') {
                    document.getElementById('btnEmailYes').classList.add('active');
                    document.getElementById('btnEmailNo').classList.remove('active');
                } else {
                    document.getElementById('btnEmpIdYes').classList.add('active');
                    document.getElementById('btnEmpIdNo').classList.remove('active');
                }
            } else {
                field.classList.remove('show');
                input.value = ''; // Clear the field when hiding
                // Update button states
                if (fieldName === 'email') {
                    document.getElementById('btnEmailYes').classList.remove('active');
                    document.getElementById('btnEmailNo').classList.add('active');
                } else {
                    document.getElementById('btnEmpIdYes').classList.remove('active');
                    document.getElementById('btnEmpIdNo').classList.add('active');
                }
            }
        }

        form.addEventListener('submit', async (e) => {
            e.preventDefault();

            const t = translations[currentLanguage];

            // Get form data
            const formData = {
                timestamp: new Date().toLocaleString(),
                name: document.getElementById('name').value.trim(),
                email: document.getElementById('email').value.trim() || 'Not provided',
                employeeId: document.getElementById('employeeId').value.trim() || 'Not provided',
                department: document.getElementById('department').value,
                kaizenIdea: document.getElementById('kaizenIdea').value.trim(),
                category: document.getElementById('category').value || 'Not specified'
            };

            // Show loading
            submitBtn.disabled = true;
            submitBtn.textContent = t.submitting;
            loading.classList.add('active');
            message.style.display = 'none';

            try {
                const response = await fetch(GOOGLE_SCRIPT_URL, {
                    method: 'POST',
                    mode: 'no-cors',
                    headers: {
                        'Content-Type': 'application/json',
                    },
                    body: JSON.stringify(formData)
                });

                // Since we're using no-cors, we can't read the response
                // We'll assume success if no error was thrown
                showMessage(t.successMsg, 'success');
                form.reset();
                // Reset optional fields
                toggleOptionalField('email', false);
                toggleOptionalField('employeeId', false);

            } catch (error) {
                console.error('Error:', error);
                showMessage(t.errorMsg, 'error');
            } finally {
                submitBtn.disabled = false;
                submitBtn.textContent = t.submitBtn;
                loading.classList.remove('active');
            }
        });

        function showMessage(text, type) {
            message.textContent = text;
            message.className = `message ${type}`;
            message.style.display = 'block';

            if (type === 'success') {
                setTimeout(() => {
                    message.style.display = 'none';
                }, 5000);
            }
        }
    </script>
</body>
</html>
