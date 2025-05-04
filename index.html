<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ClaimBook | Insurance Reimbursement Module</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Add QuaggaJS for barcode scanning -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/quagga/0.12.1/quagga.min.js"></script>
    <style>
        :root {
            --primary-color: #4e73df;
            --secondary-color: #1cc88a;
            --danger-color: #e74a3b;
            --warning-color: #f6c23e;
            --info-color: #36b9cc;
            --light-color: #f8f9fc;
            --dark-color: #5a5c69;
            --text-color: #333;
            --text-light: #858796;
            --bg-color: #f8f9fc;
            --card-bg: #fff;
            --border-color: #e3e6f0;
        }

        .dark-mode {
            --primary-color: #4e73df;
            --secondary-color: #1cc88a;
            --danger-color: #e74a3b;
            --warning-color: #f6c23e;
            --info-color: #36b9cc;
            --light-color: #2a2b3a;
            --dark-color: #d1d3e2;
            --text-color: #f8f9fc;
            --text-light: #b7b9cc;
            --bg-color: #1a1a2e;
            --card-bg: #16213e;
            --border-color: #2d3748;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: background-color 0.3s, color 0.3s;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
            border-bottom: 1px solid var(--border-color);
            margin-bottom: 30px;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo i {
            font-size: 28px;
            color: var(--primary-color);
        }

        .logo h1 {
            font-size: 24px;
            font-weight: 700;
            background: linear-gradient(45deg, var(--primary-color), var(--secondary-color));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }

        .theme-toggle {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 20px;
            padding: 5px 10px;
            display: flex;
            align-items: center;
            gap: 5px;
            cursor: pointer;
        }

        .theme-toggle i {
            font-size: 16px;
        }

        .main-content {
            display: grid;
            grid-template-columns: 250px 1fr;
            gap: 20px;
        }

        .sidebar {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.05);
            height: fit-content;
        }

        .sidebar-menu {
            list-style: none;
        }

        .sidebar-menu li {
            margin-bottom: 10px;
        }

        .sidebar-menu a {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 10px;
            border-radius: 5px;
            color: var(--text-color);
            text-decoration: none;
            transition: all 0.2s;
        }

        .sidebar-menu a:hover, .sidebar-menu a.active {
            background: var(--primary-color);
            color: white;
        }

        .sidebar-menu i {
            font-size: 18px;
        }

        .content-area {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.05);
        }

        .card-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 1px solid var(--border-color);
        }

        .card-header h2 {
            font-size: 20px;
            font-weight: 600;
            color: var(--primary-color);
        }

        .card-header .badge {
            background: var(--secondary-color);
            color: white;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            color: var(--text-color);
        }

        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid var(--border-color);
            border-radius: 5px;
            background: var(--card-bg);
            color: var(--text-color);
            font-size: 14px;
        }

        .form-control:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px rgba(78, 115, 223, 0.25);
        }

        .row {
            display: flex;
            gap: 20px;
        }

        .col {
            flex: 1;
        }

        .btn {
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.2s;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }

        .btn-primary {
            background: var(--primary-color);
            color: white;
        }

        .btn-primary:hover {
            background: #3a5ccc;
        }

        .btn-secondary {
            background: var(--secondary-color);
            color: white;
        }

        .btn-secondary:hover {
            background: #17a673;
        }

        .btn-danger {
            background: var(--danger-color);
            color: white;
        }

        .btn-danger:hover {
            background: #d23a2b;
        }

        .btn-outline {
            background: transparent;
            border: 1px solid var(--border-color);
            color: var(--text-color);
        }

        .btn-outline:hover {
            background: var(--border-color);
        }

        .alert {
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .alert-info {
            background: rgba(54, 185, 204, 0.1);
            border-left: 4px solid var(--info-color);
            color: var(--text-color);
        }

        .alert-warning {
            background: rgba(246, 194, 62, 0.1);
            border-left: 4px solid var(--warning-color);
            color: var(--text-color);
        }

        .alert i {
            font-size: 20px;
        }

        .table-responsive {
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid var(--border-color);
        }

        th {
            background: rgba(78, 115, 223, 0.1);
            color: var(--primary-color);
            font-weight: 600;
        }

        tr:hover {
            background: rgba(78, 115, 223, 0.05);
        }

        .status-badge {
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
        }

        .status-pending {
            background: rgba(246, 194, 62, 0.1);
            color: var(--warning-color);
        }

        .status-approved {
            background: rgba(28, 200, 138, 0.1);
            color: var(--secondary-color);
        }

        .status-rejected {
            background: rgba(231, 74, 59, 0.1);
            color: var(--danger-color);
        }

        .login-container {
            max-width: 500px;
            margin: 50px auto;
            background: var(--card-bg);
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        }

        .login-header {
            text-align: center;
            margin-bottom: 30px;
        }

        .login-header h2 {
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        .login-header p {
            color: var(--text-light);
        }

        .otp-container {
            display: none;
            margin-top: 20px;
        }

        .otp-input {
            display: flex;
            gap: 10px;
            justify-content: center;
        }

        .otp-input input {
            width: 40px;
            height: 40px;
            text-align: center;
            font-size: 18px;
            border: 1px solid var(--border-color);
            border-radius: 5px;
            background: var(--card-bg);
            color: var(--text-color);
        }

        .otp-input input:focus {
            outline: none;
            border-color: var(--primary-color);
        }

        .progress-steps {
            display: flex;
            justify-content: space-between;
            margin-bottom: 30px;
            position: relative;
        }

        .progress-steps::before {
            content: '';
            position: absolute;
            top: 15px;
            left: 0;
            right: 0;
            height: 2px;
            background: var(--border-color);
            z-index: 1;
        }

        .step {
            display: flex;
            flex-direction: column;
            align-items: center;
            position: relative;
            z-index: 2;
        }

        .step-number {
            width: 30px;
            height: 30px;
            border-radius: 50%;
            background: var(--border-color);
            color: var(--text-light);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 600;
            margin-bottom: 5px;
        }

        .step.active .step-number {
            background: var(--primary-color);
            color: white;
        }

        .step.completed .step-number {
            background: var(--secondary-color);
            color: white;
        }

        .step-label {
            font-size: 12px;
            color: var(--text-light);
            text-align: center;
        }

        .step.active .step-label {
            color: var(--primary-color);
            font-weight: 600;
        }

        .step.completed .step-label {
            color: var(--secondary-color);
        }

        .hidden {
            display: none;
        }

        .amount-card {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 20px;
            border-left: 4px solid var(--primary-color);
            margin-bottom: 20px;
        }

        .amount-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .amount-label {
            color: var(--text-light);
        }

        .amount-value {
            font-weight: 600;
        }

        .total-amount {
            border-top: 1px solid var(--border-color);
            padding-top: 10px;
            margin-top: 10px;
            font-size: 18px;
        }

        .payment-options {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            margin-top: 20px;
        }

        .payment-option {
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 15px;
            cursor: pointer;
            transition: all 0.2s;
        }

        .payment-option:hover {
            border-color: var(--primary-color);
            background: rgba(78, 115, 223, 0.05);
        }

        .payment-option.selected {
            border-color: var(--primary-color);
            background: rgba(78, 115, 223, 0.1);
        }

        .payment-option i {
            font-size: 24px;
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        .payment-option h4 {
            margin-bottom: 5px;
        }

        .payment-option p {
            font-size: 12px;
            color: var(--text-light);
        }

        /* New Styles for Added Features */
        .tabs {
            display: flex;
            border-bottom: 1px solid var(--border-color);
            margin-bottom: 20px;
        }

        .tab {
            padding: 10px 20px;
            cursor: pointer;
            border-bottom: 2px solid transparent;
        }

        .tab.active {
            border-bottom: 2px solid var(--primary-color);
            color: var(--primary-color);
            font-weight: 600;
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
        }

        .review-section {
            margin-bottom: 30px;
            padding: 20px;
            background: rgba(78, 115, 223, 0.05);
            border-radius: 8px;
            border-left: 4px solid var(--primary-color);
        }

        .review-section h3 {
            margin-bottom: 15px;
            color: var(--primary-color);
        }

        .review-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
        }

        .review-item {
            margin-bottom: 10px;
        }

        .review-item strong {
            display: inline-block;
            min-width: 180px;
        }

        .document-types {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            margin-top: 15px;
        }

        .document-type {
            border: 1px dashed var(--border-color);
            padding: 15px;
            border-radius: 8px;
        }

        .document-type h4 {
            margin-bottom: 10px;
            font-size: 14px;
        }

        .bill-breakup {
            margin-top: 20px;
        }

        .bill-breakup table {
            width: 100%;
            margin-top: 10px;
        }

        .bill-breakup th {
            background: rgba(78, 115, 223, 0.1);
        }

        .bill-breakup td, .bill-breakup th {
            padding: 10px;
        }

        .add-item-btn {
            margin-top: 10px;
        }

        .chatbot {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 350px;
            background: var(--card-bg);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            z-index: 1000;
            display: none;
            flex-direction: column;
            border: 1px solid var(--border-color);
        }

        .chatbot-header {
            padding: 15px;
            background: var(--primary-color);
            color: white;
            border-radius: 10px 10px 0 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .chatbot-body {
            padding: 15px;
            height: 300px;
            overflow-y: auto;
        }

        .chatbot-footer {
            padding: 15px;
            border-top: 1px solid var(--border-color);
        }

        .chatbot-input {
            width: 100%;
            padding: 10px;
            border: 1px solid var(--border-color);
            border-radius: 20px;
        }

        .chatbot-toggle {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
            background: var(--primary-color);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            z-index: 1001;
        }

        .message {
            margin-bottom: 15px;
            max-width: 80%;
        }

        .bot-message {
            align-self: flex-start;
            background: rgba(78, 115, 223, 0.1);
            padding: 10px 15px;
            border-radius: 0 15px 15px 15px;
        }

        .user-message {
            align-self: flex-end;
            background: var(--primary-color);
            color: white;
            padding: 10px 15px;
            border-radius: 15px 0 15px 15px;
        }

        .cibil-score {
            display: flex;
            align-items: center;
            gap: 15px;
            margin-top: 15px;
            padding: 15px;
            background: rgba(28, 200, 138, 0.1);
            border-radius: 8px;
        }

        .cibil-score-value {
            font-size: 24px;
            font-weight: 700;
            color: var(--secondary-color);
        }

        .cibil-rating {
            font-size: 14px;
            color: var(--text-light);
        }

        .early-pay-options {
            margin-top: 20px;
        }

        .early-pay-option {
            display: flex;
            justify-content: space-between;
            padding: 15px;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            margin-bottom: 10px;
            cursor: pointer;
        }

        .early-pay-option.selected {
            border-color: var(--primary-color);
            background: rgba(78, 115, 223, 0.1);
        }

        .early-pay-option h4 {
            margin-bottom: 5px;
        }

        .early-pay-option p {
            font-size: 12px;
            color: var(--text-light);
        }

        .faq-item {
            margin-bottom: 20px;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 20px;
        }

        .faq-question {
            font-weight: 600;
            margin-bottom: 10px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .faq-answer {
            display: none;
            padding-top: 10px;
        }

        .faq-answer.show {
            display: block;
        }

        .blog-card {
            margin-bottom: 20px;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            overflow: hidden;
        }

        .blog-image {
            height: 150px;
            background: var(--border-color);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text-light);
        }

        .blog-content {
            padding: 15px;
        }

        .blog-title {
            font-weight: 600;
            margin-bottom: 10px;
        }

        .blog-meta {
            font-size: 12px;
            color: var(--text-light);
            margin-bottom: 10px;
        }

        .blog-excerpt {
            font-size: 14px;
            margin-bottom: 10px;
        }

        .ticket-card {
            margin-bottom: 15px;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 15px;
        }

        .ticket-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .ticket-title {
            font-weight: 600;
        }

        .ticket-status {
            padding: 3px 8px;
            border-radius: 12px;
            font-size: 12px;
        }

        .status-open {
            background: rgba(246, 194, 62, 0.1);
            color: var(--warning-color);
        }

        .status-resolved {
            background: rgba(28, 200, 138, 0.1);
            color: var(--secondary-color);
        }

        .ticket-meta {
            font-size: 12px;
            color: var(--text-light);
            margin-bottom: 10px;
        }

        .ticket-description {
            font-size: 14px;
        }

        /* New Styles for Document Scanning */
        .scan-section {
            margin-top: 15px;
            border: 1px dashed var(--border-color);
            padding: 15px;
            border-radius: 8px;
            text-align: center;
        }
        
        .scan-preview {
            width: 100%;
            max-width: 300px;
            height: auto;
            margin: 10px auto;
            display: none;
            border: 1px solid var(--border-color);
        }
        
        .scan-buttons {
            display: flex;
            gap: 10px;
            justify-content: center;
            margin-top: 10px;
        }
        
        .scan-btn {
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 5px;
            font-size: 14px;
        }
        
        .scan-btn-primary {
            background: var(--primary-color);
            color: white;
            border: none;
        }
        
        .scan-btn-outline {
            background: transparent;
            border: 1px solid var(--border-color);
            color: var(--text-color);
        }
        
        #scanner-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.8);
            z-index: 2000;
            display: none;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        
        #scanner-viewport {
            width: 80%;
            max-width: 500px;
            height: 300px;
            background: black;
            position: relative;
            margin-bottom: 20px;
        }
        
        #scanner-controls {
            display: flex;
            gap: 15px;
        }
        
        /* Settlement Styles */
        .settlement-card {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            border-left: 4px solid var(--secondary-color);
        }
        
        .settlement-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 15px;
        }
        
        .settlement-details {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
        }
        
        .settlement-item {
            margin-bottom: 10px;
        }
        
        .settlement-item strong {
            display: inline-block;
            min-width: 150px;
        }
        
        .reconciliation-table {
            margin-top: 20px;
        }
        
        .action-buttons {
            display: flex;
            gap: 10px;
            justify-content: flex-end;
            margin-top: 20px;
        }
        
        .ocr-processing {
            display: none;
            text-align: center;
            padding: 20px;
        }
        
        .ocr-processing i {
            font-size: 40px;
            color: var(--primary-color);
            margin-bottom: 10px;
            animation: spin 1s linear infinite;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }

            .row {
                flex-direction: column;
                gap: 0;
            }

            .payment-options {
                grid-template-columns: 1fr;
            }

            .review-grid {
                grid-template-columns: 1fr;
            }

            .document-types {
                grid-template-columns: 1fr;
            }

            .chatbot {
                width: 90%;
                right: 5%;
            }

            #scanner-viewport {
                width: 95%;
                height: 250px;
            }
        }
    </style>
</head>
<body>
    <!-- Login Screen (Initial View) -->
    <div id="login-screen" class="container">
        <div class="login-container">
            <div class="login-header">
                <div class="logo">
                    <i class="fas fa-file-invoice-dollar"></i>
                    <h1>ClaimBook</h1>
                </div>
                <h2>Insurance Reimbursement Portal</h2>
                <p>Access your account to manage insurance claims</p>
            </div>
            
            <form id="login-form">
                <div class="form-group">
                    <label for="username">Username</label>
                    <input type="text" id="username" class="form-control" placeholder="Enter your username" required>
                </div>
                
                <div class="form-group">
                    <label for="mobile">Mobile Number</label>
                    <input type="tel" id="mobile" class="form-control" placeholder="Enter your mobile number" required>
                </div>
                
                <div class="form-group">
                    <label for="email">Email ID</label>
                    <input type="email" id="email" class="form-control" placeholder="Enter your email address" required>
                </div>
                
                <button type="button" id="send-otp-btn" class="btn btn-primary btn-block">
                    <i class="fas fa-paper-plane"></i> Send OTP
                </button>
                
                <div id="otp-container" class="otp-container">
                    <div class="form-group">
                        <label for="otp">Enter OTP</label>
                        <div class="otp-input">
                            <input type="text" maxlength="1" pattern="\d">
                            <input type="text" maxlength="1" pattern="\d">
                            <input type="text" maxlength="1" pattern="\d">
                            <input type="text" maxlength="1" pattern="\d">
                            <input type="text" maxlength="1" pattern="\d">
                            <input type="text" maxlength="1" pattern="\d">
                        </div>
                    </div>
                    
                    <button type="button" id="verify-otp-btn" class="btn btn-secondary btn-block">
                        <i class="fas fa-check-circle"></i> Verify OTP
                    </button>
                </div>
            </form>
        </div>
    </div>
    
    <!-- Main Application (Hidden Initially) -->
    <div id="main-application" class="container hidden">
        <header>
            <div class="logo">
                <i class="fas fa-file-invoice-dollar"></i>
                <h1>ClaimBook</h1>
            </div>
            
            <div class="user-actions">
                <button id="theme-toggle" class="theme-toggle">
                    <i class="fas fa-moon"></i>
                    <span>Dark Mode</span>
                </button>
            </div>
        </header>
        
        <div class="main-content">
            <div class="sidebar">
                <ul class="sidebar-menu">
                    <li><a href="#" class="active" id="dashboard-link"><i class="fas fa-tachometer-alt"></i> Dashboard</a></li>
                    <li><a href="#" id="new-claim-link"><i class="fas fa-plus-circle"></i> New Claim</a></li>
                    <li><a href="#" id="transactions-link"><i class="fas fa-exchange-alt"></i> Transactions</a></li>
                    <li><a href="#" id="tickets-link"><i class="fas fa-ticket-alt"></i> Support Tickets</a></li>
                    <li><a href="#" id="faqs-link"><i class="fas fa-question-circle"></i> FAQs</a></li>
                    <li><a href="#" id="blogs-link"><i class="fas fa-blog"></i> Blogs</a></li>
                    <li><a href="#" id="settlement-link"><i class="fas fa-file-invoice-dollar"></i> Settlement</a></li>
                    <li><a href="#" id="settings-link"><i class="fas fa-cog"></i> Settings</a></li>
                    <li><a href="#" id="logout-link"><i class="fas fa-sign-out-alt"></i> Logout</a></li>
                </ul>
            </div>
            
            <div class="content-area">
                <!-- Dashboard Content -->
                <div id="dashboard-content">
                    <div class="card">
                        <div class="card-header">
                            <h2>Insurance Reimbursement Dashboard</h2>
                            <span class="badge">Hospital Admin</span>
                        </div>
                        
                        <div class="alert alert-info">
                            <i class="fas fa-info-circle"></i>
                            <div>
                                <strong>Welcome to ClaimBook Reimbursement Module</strong>
                                <p>This portal helps you manage insurance claims for patients even when your hospital is not empanelled with their insurance provider.</p>
                            </div>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="card">
                                    <div class="card-header">
                                        <h2>Quick Actions</h2>
                                    </div>
                                    <div class="form-group">
                                        <button class="btn btn-primary" id="start-new-claim-btn">
                                            <i class="fas fa-plus"></i> Start New Claim
                                        </button>
                                    </div>
                                    <div class="form-group">
                                        <button class="btn btn-secondary">
                                            <i class="fas fa-search"></i> Search Patient
                                        </button>
                                    </div>
                                    <div class="form-group">
                                        <button class="btn btn-outline">
                                            <i class="fas fa-file-export"></i> Export Reports
                                        </button>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="col">
                                <div class="card">
                                    <div class="card-header">
                                        <h2>Statistics</h2>
                                    </div>
                                    <div class="row">
                                        <div class="col">
                                            <div class="amount-card">
                                                <div class="amount-row">
                                                    <span class="amount-label">Pending Claims</span>
                                                    <span class="amount-value">12</span>
                                                </div>
                                                <div class="amount-row">
                                                    <span class="amount-label">Approved This Month</span>
                                                    <span class="amount-value">24</span>
                                                </div>
                                                <div class="amount-row">
                                                    <span class="amount-label">Rejected This Month</span>
                                                    <span class="amount-value">5</span>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="card">
                            <div class="card-header">
                                <h2>Recent Claims</h2>
                            </div>
                            <div class="table-responsive">
                                <table>
                                    <thead>
                                        <tr>
                                            <th>Claim ID</th>
                                            <th>Patient Name</th>
                                            <th>Insurance Provider</th>
                                            <th>Billed Amount</th>
                                            <th>Approved Amount</th>
                                            <th>Status</th>
                                            <th>Action</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>#CB-2023-001</td>
                                            <td>John Doe</td>
                                            <td>Star Health</td>
                                            <td>₹25,000</td>
                                            <td>₹22,500</td>
                                            <td><span class="status-badge status-approved">Approved</span></td>
                                            <td><button class="btn btn-outline btn-sm view-case-btn">View</button></td>
                                        </tr>
                                        <tr>
                                            <td>#CB-2023-002</td>
                                            <td>Jane Smith</td>
                                            <td>HDFC Ergo</td>
                                            <td>₹18,750</td>
                                            <td>₹15,000</td>
                                            <td><span class="status-badge status-pending">Pending</span></td>
                                            <td><button class="btn btn-outline btn-sm view-case-btn">View</button></td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- New Claim Content -->
                <div id="new-claim-content" class="hidden">
                    <div class="progress-steps">
                        <div class="step active" id="step1">
                            <div class="step-number">1</div>
                            <div class="step-label">Patient Details</div>
                        </div>
                        <div class="step" id="step2">
                            <div class="step-number">2</div>
                            <div class="step-label">Insurance Info</div>
                        </div>
                        <div class="step" id="step3">
                            <div class="step-number">3</div>
                            <div class="step-label">Treatment Details</div>
                        </div>
                        <div class="step" id="step4">
                            <div class="step-number">4</div>
                            <div class="step-label">Billing & Payment</div>
                        </div>
                        <div class="step" id="step5">
                            <div class="step-number">5</div>
                            <div class="step-label">Review & Submit</div>
                        </div>
                    </div>
                    
                    <!-- Step 1: Patient Details -->
                    <div class="card step-content" id="step1-content">
                        <div class="card-header">
                            <h2>Patient Details</h2>
                        </div>
                        
                        <div class="alert alert-warning">
                            <i class="fas fa-exclamation-circle"></i>
                            <div>
                                <strong>Important:</strong> Please ensure all patient details are accurate as they will be used for insurance claim processing.
                            </div>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="form-group">
                                    <label for="patient-name">Full Name</label>
                                    <input type="text" id="patient-name" class="form-control" placeholder="Enter patient's full name">
                                </div>
                            </div>
                            <div class="col">
                                <div class="form-group">
                                    <label for="patient-dob">Date of Birth</label>
                                    <input type="date" id="patient-dob" class="form-control">
                                </div>
                            </div>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="form-group">
                                    <label for="patient-gender">Gender</label>
                                    <select id="patient-gender" class="form-control">
                                        <option value="">Select Gender</option>
                                        <option value="male">Male</option>
                                        <option value="female">Female</option>
                                        <option value="other">Other</option>
                                    </select>
                                </div>
                            </div>
                            <div class="col">
                                <div class="form-group">
                                    <label for="patient-mobile">Mobile Number</label>
                                    <input type="tel" id="patient-mobile" class="form-control" placeholder="Enter mobile number">
                                </div>
                            </div>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="form-group">
                                    <label for="mr-number">MR Number</label>
                                    <input type="text" id="mr-number" class="form-control" placeholder="Enter MR number">
                                </div>
                            </div>
                            <div class="col">
                                <div class="form-group">
                                    <label for="case-id">Case ID</label>
                                    <input type="text" id="case-id" class="form-control" placeholder="Enter case ID">
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="patient-address">Address</label>
                            <textarea id="patient-address" class="form-control" rows="3" placeholder="Enter full address"></textarea>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="form-group">
                                    <label for="patient-city">City</label>
                                    <input type="text" id="patient-city" class="form-control" placeholder="Enter city">
                                </div>
                            </div>
                            <div class="col">
                                <div class="form-group">
                                    <label for="patient-state">State</label>
                                    <input type="text" id="patient-state" class="form-control" placeholder="Enter state">
                                </div>
                            </div>
                            <div class="col">
                                <div class="form-group">
                                    <label for="patient-pincode">Pincode</label>
                                    <input type="text" id="patient-pincode" class="form-control" placeholder="Enter pincode">
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="patient-aadhar">Aadhar Number (Optional)</label>
                            <input type="text" id="patient-aadhar" class="form-control" placeholder="Enter Aadhar number if available">
                        </div>
                        
                        <div class="form-group text-right">
                            <button class="btn btn-primary" id="step1-next">
                                Next <i class="fas fa-arrow-right"></i>
                            </button>
                        </div>
                    </div>
                    
                    <!-- Step 2: Insurance Information -->
                    <div class="card step-content hidden" id="step2-content">
                        <div class="card-header">
                            <h2>Insurance Information</h2>
                        </div>
                        
                        <div class="alert alert-info">
                            <i class="fas fa-info-circle"></i>
                            <div>
                                <strong>Note:</strong> This information will be used to verify coverage and process the claim with the insurance provider.
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label>Insurance Card Scan</label>
                            <div class="scan-section">
                                <div id="insuranceCard-scan-preview" class="scan-preview"></div>
                                <div class="scan-buttons">
                                    <button class="scan-btn scan-btn-primary" onclick="startScanner('insuranceCard')">
                                        <i class="fas fa-camera"></i> Scan Insurance Card
                                    </button>
                                    <button class="scan-btn scan-btn-outline" onclick="document.getElementById('insuranceCard-file').click()">
                                        <i class="fas fa-upload"></i> Upload Insurance Card
                                    </button>
                                </div>
                                <input type="file" id="insuranceCard-file" class="hidden" accept="image/*,.pdf" onchange="handleInsuranceCardUpload(this)">
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="insurance-provider">Insurance Provider</label>
                            <select id="insurance-provider" class="form-control">
                                <option value="">Select Insurance Provider</option>
                                <option value="star_health">Star Health</option>
                                <option value="hdfc_ergo">HDFC Ergo</option>
                                <option value="icici_lombard">ICICI Lombard</option>
                                <option value="bajaj_allianz">Bajaj Allianz</option>
                                <option value="reliance_general">Reliance General</option>
                                <option value="other">Other</option>
                            </select>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="form-group">
                                    <label for="policy-number">Policy Number</label>
                                    <input type="text" id="policy-number" class="form-control" placeholder="Enter policy number">
                                </div>
                            </div>
                            <div class="col">
                                <div class="form-group">
                                    <label for="policy-holder">Policy Holder Name</label>
                                    <input type="text" id="policy-holder" class="form-control" placeholder="Enter policy holder's name">
                                </div>
                            </div>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="form-group">
                                    <label for="policy-start">Policy Start Date</label>
                                    <input type="date" id="policy-start" class="form-control">
                                </div>
                            </div>
                            <div class="col">
                                <div class="form-group">
                                    <label for="policy-end">Policy End Date</label>
                                    <input type="date" id="policy-end" class="form-control">
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="sum-insured">Sum Insured</label>
                            <input type="text" id="sum-insured" class="form-control" placeholder="Enter total sum insured">
                        </div>
                        
                        <div class="form-group">
                            <label for="tpa-name">TPA Name (If Applicable)</label>
                            <input type="text" id="tpa-name" class="form-control" placeholder="Enter TPA name if applicable">
                        </div>
                        
                        <div class="form-group">
                            <label for="tpa-id">TPA ID (If Applicable)</label>
                            <input type="text" id="tpa-id" class="form-control" placeholder="Enter TPA ID if applicable">
                        </div>
                        
                        <div class="form-group">
                            <label>
                                <input type="checkbox" id="consent-checkbox"> 
                                I confirm that the patient has provided consent to process this insurance claim on their behalf
                            </label>
                        </div>
                        
                        <div class="form-group text-right">
                            <button class="btn btn-outline" id="step2-back">
                                <i class="fas fa-arrow-left"></i> Back
                            </button>
                            <button class="btn btn-primary" id="step2-next">
                                Next <i class="fas fa-arrow-right"></i>
                            </button>
                        </div>
                    </div>
                    
                    <!-- Step 3: Treatment Details -->
                    <div class="card step-content hidden" id="step3-content">
                        <div class="card-header">
                            <h2>Treatment Details</h2>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="form-group">
                                    <label for="admission-date">Admission Date</label>
                                    <input type="date" id="admission-date" class="form-control">
                                </div>
                            </div>
                            <div class="col">
                                <div class="form-group">
                                    <label for="discharge-date">Discharge Date</label>
                                    <input type="date" id="discharge-date" class="form-control">
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="room-type">Room Type</label>
                            <select id="room-type" class="form-control">
                                <option value="">Select Room Type</option>
                                <option value="general">General Ward</option>
                                <option value="semi_private">Semi-Private</option>
                                <option value="private">Private</option>
                                <option value="deluxe">Deluxe</option>
                                <option value="icu">ICU</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="diagnosis">Primary Diagnosis</label>
                            <input type="text" id="diagnosis" class="form-control" placeholder="Enter primary diagnosis">
                        </div>
                        
                        <div class="form-group">
                            <label for="treatment-details">Treatment Details</label>
                            <textarea id="treatment-details" class="form-control" rows="3" placeholder="Describe the treatment provided"></textarea>
                        </div>
                        
                        <div class="form-group">
                            <label for="doctor-name">Treating Doctor</label>
                            <input type="text" id="doctor-name" class="form-control" placeholder="Enter doctor's name">
                        </div>
                        
                        <div class="form-group">
                            <label for="icd-code">ICD Code (If Known)</label>
                            <input type="text" id="icd-code" class="form-control" placeholder="Enter ICD code if known">
                        </div>
                        
                        <div class="form-group">
                            <label>Upload Documents</label>
                            <div class="document-types">
                                <div class="document-type">
                                    <h4>Part A claim form</h4>
                                    <div class="scan-section">
                                        <div id="partA-scan-preview" class="scan-preview"></div>
                                        <div class="scan-buttons">
                                            <button class="scan-btn scan-btn-primary" onclick="startScanner('partA')">
                                                <i class="fas fa-camera"></i> Scan Document
                                            </button>
                                            <button class="scan-btn scan-btn-outline" onclick="document.getElementById('partA-file').click()">
                                                <i class="fas fa-upload"></i> Upload File
                                            </button>
                                        </div>
                                        <input type="file" id="partA-file" class="hidden" accept="image/*,.pdf" onchange="handleFileUpload(this, 'partA')">
                                    </div>
                                </div>
                                <div class="document-type">
                                    <h4>Photo ID card</h4>
                                    <div class="scan-section">
                                        <div id="photoId-scan-preview" class="scan-preview"></div>
                                        <div class="scan-buttons">
                                            <button class="scan-btn scan-btn-primary" onclick="startScanner('photoId')">
                                                <i class="fas fa-camera"></i> Scan Document
                                            </button>
                                            <button class="scan-btn scan-btn-outline" onclick="document.getElementById('photoId-file').click()">
                                                <i class="fas fa-upload"></i> Upload File
                                            </button>
                                        </div>
                                        <input type="file" id="photoId-file" class="hidden" accept="image/*,.pdf" onchange="handleFileUpload(this, 'photoId')">
                                    </div>
                                </div>
                                <div class="document-type">
                                    <h4>Final main bill with Patient signature</h4>
                                    <div class="scan-section">
                                        <div id="finalBill-scan-preview" class="scan-preview"></div>
                                        <div class="scan-buttons">
                                            <button class="scan-btn scan-btn-primary" onclick="startScanner('finalBill')">
                                                <i class="fas fa-camera"></i> Scan Document
                                            </button>
                                            <button class="scan-btn scan-btn-outline" onclick="document.getElementById('finalBill-file').click()">
                                                <i class="fas fa-upload"></i> Upload File
                                            </button>
                                        </div>
                                        <input type="file" id="finalBill-file" class="hidden" accept="image/*,.pdf" onchange="handleFileUpload(this, 'finalBill')">
                                    </div>
                                </div>
                                <div class="document-type">
                                    <h4>Detailed break up of bill</h4>
                                    <div class="scan-section">
                                        <div id="billBreakup-scan-preview" class="scan-preview"></div>
                                        <div class="scan-buttons">
                                            <button class="scan-btn scan-btn-primary" onclick="startScanner('billBreakup')">
                                                <i class="fas fa-camera"></i> Scan Document
                                            </button>
                                            <button class="scan-btn scan-btn-outline" onclick="document.getElementById('billBreakup-file').click()">
                                                <i class="fas fa-upload"></i> Upload File
                                            </button>
                                        </div>
                                        <input type="file" id="billBreakup-file" class="hidden" accept="image/*,.pdf" onchange="handleFileUpload(this, 'billBreakup')">
                                    </div>
                                </div>
                                <div class="document-type">
                                    <h4>Patient paid receipt</h4>
                                    <div class="scan-section">
                                        <div id="receipt-scan-preview" class="scan-preview"></div>
                                        <div class="scan-buttons">
                                            <button class="scan-btn scan-btn-primary" onclick="startScanner('receipt')">
                                                <i class="fas fa-camera"></i> Scan Document
                                            </button>
                                            <button class="scan-btn scan-btn-outline" onclick="document.getElementById('receipt-file').click()">
                                                <i class="fas fa-upload"></i> Upload File
                                            </button>
                                        </div>
                                        <input type="file" id="receipt-file" class="hidden" accept="image/*,.pdf" onchange="handleFileUpload(this, 'receipt')">
                                    </div>
                                </div>
                                <div class="document-type">
                                    <h4>Discharge summary with treating Dr seal and signature</h4>
                                    <div class="scan-section">
                                        <div id="discharge-scan-preview" class="scan-preview"></div>
                                        <div class="scan-buttons">
                                            <button class="scan-btn scan-btn-primary" onclick="startScanner('discharge')">
                                                <i class="fas fa-camera"></i> Scan Document
                                            </button>
                                            <button class="scan-btn scan-btn-outline" onclick="document.getElementById('discharge-file').click()">
                                                <i class="fas fa-upload"></i> Upload File
                                            </button>
                                        </div>
                                        <input type="file" id="discharge-file" class="hidden" accept="image/*,.pdf" onchange="handleFileUpload(this, 'discharge')">
                                    </div>
                                </div>
                                <div class="document-type">
                                    <h4>Investigation Reports</h4>
                                    <div class="scan-section">
                                        <div id="reports-scan-preview" class="scan-preview"></div>
                                        <div class="scan-buttons">
                                            <button class="scan-btn scan-btn-primary" onclick="startScanner('reports')">
                                                <i class="fas fa-camera"></i> Scan Document
                                            </button>
                                            <button class="scan-btn scan-btn-outline" onclick="document.getElementById('reports-file').click()">
                                                <i class="fas fa-upload"></i> Upload File
                                            </button>
                                        </div>
                                        <input type="file" id="reports-file" class="hidden" accept="image/*,.pdf" onchange="handleFileUpload(this, 'reports')">
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group text-right">
                            <button class="btn btn-outline" id="step3-back">
                                <i class="fas fa-arrow-left"></i> Back
                            </button>
                            <button class="btn btn-primary" id="step3-next">
                                Next <i class="fas fa-arrow-right"></i>
                            </button>
                        </div>
                    </div>
                    
                    <!-- Step 4: Billing & Payment -->
                    <div class="card step-content hidden" id="step4-content">
                        <div class="card-header">
                            <h2>Billing & Payment</h2>
                        </div>
                        
                        <div class="row">
                            <div class="col">
                                <div class="amount-card">
                                    <div class="amount-row">
                                        <span class="amount-label">Total Billed Amount</span>
                                        <span class="amount-value">₹25,000</span>
                                    </div>
                                    <div class="amount-row">
                                        <span class="amount-label">Estimated Approved Amount</span>
                                        <span class="amount-value">₹22,500</span>
                                    </div>
                                    <div class="amount-row">
                                        <span class="amount-label">Deductible/Co-pay</span>
                                        <span class="amount-value">₹2,500</span>
                                    </div>
                                    <div class="amount-row total-amount">
                                        <span class="amount-label">Patient Responsibility</span>
                                        <span class="amount-value">₹5,000</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="bill-breakup">
                            <h4>Bill Breakup</h4>
                            <table>
                                <thead>
                                    <tr>
                                        <th>Description</th>
                                        <th>Amount (₹)</th>
                                        <th>Action</th>
                                    </tr>
                                </thead>
                                <tbody id="bill-items">
                                    <tr>
                                        <td><input type="text" class="form-control" placeholder="Item description" value="Room Charges"></td>
                                        <td><input type="number" class="form-control" placeholder="Amount" value="15000"></td>
                                        <td><button class="btn btn-danger btn-sm remove-item"><i class="fas fa-trash"></i></button></td>
                                    </tr>
                                    <tr>
                                        <td><input type="text" class="form-control" placeholder="Item description" value="Surgery Charges"></td>
                                        <td><input type="number" class="form-control" placeholder="Amount" value="8000"></td>
                                        <td><button class="btn btn-danger btn-sm remove-item"><i class="fas fa-trash"></i></button></td>
                                    </tr>
                                </tbody>
                            </table>
                            <button class="btn btn-secondary btn-sm add-item-btn" id="add-bill-item">
                                <i class="fas fa-plus"></i> Add Item
                            </button>
                        </div>
                        
                        <div class="form-group">
                            <label for="payment-scenario">Select Payment Scenario</label>
                            <select id="payment-scenario" class="form-control">
                                <option value="">Select how the patient will pay</option>
                                <option value="scenario1">Patient will pay now (Reimbursement to patient later)</option>
                                <option value="scenario2">Patient cannot pay now (Hospital will claim from insurance)</option>
                                <option value="scenario3">Patient has no insurance (Loan options)</option>
                            </select>
                        </div>
                        
                        <!-- Scenario 1: Patient pays now -->
                        <div id="scenario1-details" class="hidden">
                            <div class="alert alert-info">
                                <i class="fas fa-info-circle"></i>
                                <div>
                                    <strong>Scenario:</strong> Patient will pay the full amount now. The approved insurance amount will be reimbursed to the patient's bank account later.
                                </div>
                            </div>
                            
                            <div class="form-group">
                                <label for="patient-payment-amount">Amount Patient Will Pay Now</label>
                                <input type="text" id="patient-payment-amount" class="form-control" value="₹25,000" readonly>
                            </div>
                            
                            <div class="form-group">
                                <label for="patient-bank-details">Patient Bank Details for Reimbursement</label>
                                <div class="row">
                                    <div class="col">
                                        <input type="text" class="form-control" placeholder="Bank Name">
                                    </div>
                                    <div class="col">
                                        <input type="text" class="form-control" placeholder="Account Number">
                                    </div>
                                </div>
                                <div class="row mt-2">
                                    <div class="col">
                                        <input type="text" class="form-control" placeholder="IFSC Code">
                                    </div>
                                    <div class="col">
                                        <input type="text" class="form-control" placeholder="Account Holder Name">
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Scenario 2: Patient cannot pay now -->
                        <div id="scenario2-details" class="hidden">
                            <div class="alert alert-info">
                                <i class="fas fa-info-circle"></i>
                                <div>
                                    <strong>Scenario:</strong> Patient cannot pay the full amount now. Hospital will claim from insurance and patient will pay the balance after insurance approval.
                                </div>
                            </div>
                            
                            <div class="form-group">
                                <label for="patient-minimum-payment">Minimum Amount Patient Can Pay Now</label>
                                <input type="text" id="patient-minimum-payment" class="form-control" placeholder="Enter amount patient can pay">
                            </div>
                            
                            <div class="form-group">
                                <label for="patient-payment-plan">Payment Plan for Balance Amount</label>
                                <textarea id="patient-payment-plan" class="form-control" rows="2" placeholder="Describe payment plan for remaining amount"></textarea>
                            </div>
                        </div>
                        
                        <!-- Scenario 3: Patient has no insurance -->
                        <div id="scenario3-details" class="hidden">
                            <div class="alert alert-info">
                                <i class="fas fa-info-circle"></i>
                                <div>
                                    <strong>Scenario:</strong> Patient has no insurance coverage. Please select a loan option.
                                </div>
                            </div>
                            
                            <div class="form-group">
                                <button class="btn btn-primary" id="check-eligibility-btn">
                                    <i class="fas fa-credit-card"></i> Check CIBIL Score & Eligibility
                                </button>
                            </div>
                            
                            <div class="payment-options">
                                <div class="payment-option selected">
                                    <i class="fas fa-money-bill-wave"></i>
                                    <h4>Early Pay</h4>
                                    <p>Pay within 30 days with 5% discount</p>
                                </div>
                                <div class="payment-option">
                                    <i class="fas fa-calendar-alt"></i>
                                    <h4>3 Month EMI</h4>
                                    <p>3 monthly payments at 8% interest</p>
                                </div>
                                <div class="payment-option">
                                    <i class="fas fa-calendar"></i>
                                    <h4>6 Month EMI</h4>
                                    <p>6 monthly payments at 12% interest</p>
                                </div>
                            </div>
                            
                            <div class="form-group mt-3">
                                <label for="loan-terms">
                                    <input type="checkbox" id="loan-terms"> 
                                    I agree to the loan terms and conditions
                                </label>
                            </div>
                        </div>
                        
                        <div class="form-group text-right">
                            <button class="btn btn-outline" id="step4-back">
                                <i class="fas fa-arrow-left"></i> Back
                            </button>
                            <button class="btn btn-primary" id="step4-next">
                                Next <i class="fas fa-arrow-right"></i>
                            </button>
                        </div>
                    </div>
                    
                    <!-- Step 5: Review & Submit -->
                    <div class="card step-content hidden" id="step5-content">
                        <div class="card-header">
                            <h2>Review & Submit Claim</h2>
                        </div>
                        
                        <div class="alert alert-warning">
                            <i class="fas fa-exclamation-circle"></i>
                            <div>
                                <strong>Final Review:</strong> Please review all information carefully before submitting. Incorrect information may delay claim processing.
                            </div>
                        </div>
                        
                        <div class="review-section">
                            <h3>Patient Details</h3>
                            <div class="review-grid">
                                <div class="review-item"><strong>Full Name:</strong> <span id="review-patient-name">John Doe</span></div>
                                <div class="review-item"><strong>MR Number:</strong> <span id="review-mr-number">MR-1001</span></div>
                                <div class="review-item"><strong>Case ID:</strong> <span id="review-case-id">CI-2023-001</span></div>
                                <div class="review-item"><strong>Date of Birth:</strong> <span id="review-patient-dob">15/05/1985</span></div>
                                <div class="review-item"><strong>Gender:</strong> <span id="review-patient-gender">Male</span></div>
                                <div class="review-item"><strong>Mobile:</strong> <span id="review-patient-mobile">9876543210</span></div>
                                <div class="review-item"><strong>Address:</strong> <span id="review-patient-address">123 Main St, Bangalore, Karnataka - 560001</span></div>
                            </div>
                        </div>
                        
                        <div class="review-section">
                            <h3>Insurance Information</h3>
                            <div class="review-grid">
                                <div class="review-item"><strong>Provider:</strong> <span id="review-insurance-provider">Star Health</span></div>
                                <div class="review-item"><strong>Policy No:</strong> <span id="review-policy-number">SH123456789</span></div>
                                <div class="review-item"><strong>Policy Holder:</strong> <span id="review-policy-holder">John Doe</span></div>
                                <div class="review-item"><strong>Sum Insured:</strong> <span id="review-sum-insured">₹500,000</span></div>
                                <div class="review-item"><strong>Validity:</strong> <span id="review-policy-dates">01/01/2023 - 31/12/2023</span></div>
                                <div class="review-item"><strong>TPA Name:</strong> <span id="review-tpa-name">MediAssist</span></div>
                            </div>
                        </div>
                        
                        <div class="review-section">
                            <h3>Treatment Details</h3>
                            <div class="review-grid">
                                <div class="review-item"><strong>Admission Date:</strong> <span id="review-admission-date">10/10/2023</span></div>
                                <div class="review-item"><strong>Discharge Date:</strong> <span id="review-discharge-date">15/10/2023</span></div>
                                <div class="review-item"><strong>Room Type:</strong> <span id="review-room-type">Private AC</span></div>
                                <div class="review-item"><strong>Diagnosis:</strong> <span id="review-diagnosis">Appendicitis</span></div>
                                <div class="review-item"><strong>Doctor:</strong> <span id="review-doctor">Dr. Smith</span></div>
                                <div class="review-item"><strong>Treatment:</strong> <span id="review-treatment">Laparoscopic Appendectomy</span></div>
                            </div>
                        </div>
                        
                        <div class="review-section">
                            <h3>Billing & Payment</h3>
                            <div class="review-grid">
                                <div class="review-item"><strong>Total Billed Amount:</strong> <span id="review-billed-amount">₹25,000</span></div>
                                <div class="review-item"><strong>Estimated Approved Amount:</strong> <span id="review-approved-amount">₹22,500</span></div>
                                <div class="review-item"><strong>Patient Responsibility:</strong> <span id="review-patient-responsibility">₹5,000</span></div>
                                <div class="review-item"><strong>Payment Scenario:</strong> <span id="review-payment-scenario">Patient will pay now (Reimbursement later)</span></div>
                                <div class="review-item"><strong>Payment Details:</strong> <span id="review-payment-details">Full payment at discharge</span></div>
                            </div>
                            
                            <h4 style="margin-top: 20px;">Bill Breakup</h4>
                            <table class="bill-breakup">
                                <thead>
                                    <tr>
                                        <th>Description</th>
                                        <th>Amount</th>
                                    </tr>
                                </thead>
                                <tbody id="review-bill-items">
                                    <tr>
                                        <td>Room Charges</td>
                                        <td>₹15,000</td>
                                    </tr>
                                    <tr>
                                        <td>Surgery Charges</td>
                                        <td>₹8,000</td>
                                    </tr>
                                    <tr>
                                        <td>Medicines</td>
                                        <td>₹1,500</td>
                                    </tr>
                                    <tr>
                                        <td>Diagnostics</td>
                                        <td>₹500</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                        
                        <div class="review-section">
                            <h3>Documents</h3>
                            <div class="document-types">
                                <div class="document-type">
                                    <h4>Part A claim form</h4>
                                    <span class="status-badge status-approved">Uploaded</span>
                                </div>
                                <div class="document-type">
                                    <h4>Photo ID card</h4>
                                    <span class="status-badge status-approved">Uploaded</span>
                                </div>
                                <div class="document-type">
                                    <h4>Final main bill with Patient signature</h4>
                                    <span class="status-badge status-approved">Uploaded</span>
                                </div>
                                <div class="document-type">
                                    <h4>Detailed break up of bill</h4>
                                    <span class="status-badge status-approved">Uploaded</span>
                                </div>
                                <div class="document-type">
                                    <h4>Patient paid receipt</h4>
                                    <span class="status-badge status-pending">Pending</span>
                                </div>
                                <div class="document-type">
                                    <h4>Discharge summary with treating Dr seal and signature</h4>
                                    <span class="status-badge status-approved">Uploaded</span>
                                </div>
                                <div class="document-type">
                                    <h4>Investigation Reports</h4>
                                    <span class="status-badge status-approved">Uploaded</span>
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="final-notes">Additional Notes (Optional)</label>
                            <textarea id="final-notes" class="form-control" rows="2" placeholder="Any additional information for claim processing"></textarea>
                        </div>
                        
                        <div class="form-group">
                            <label>
                                <input type="checkbox" id="final-consent"> 
                                I confirm that all information provided is accurate and I have obtained patient consent for this claim
                            </label>
                        </div>
                        
                        <div class="form-group text-right">
                            <button class="btn btn-outline" id="step5-back">
                                <i class="fas fa-arrow-left"></i> Back
                            </button>
                            <button class="btn btn-primary" id="submit-claim-btn">
                                <i class="fas fa-paper-plane"></i> Submit Claim
                            </button>
                        </div>
                    </div>
                    
                    <!-- Submission Confirmation -->
                    <div class="card step-content hidden" id="submission-confirmation">
                        <div class="card-header">
                            <h2>Claim Submitted Successfully</h2>
                        </div>
                        
                        <div class="text-center py-5">
                            <i class="fas fa-check-circle" style="font-size: 72px; color: var(--secondary-color); margin-bottom: 20px;"></i>
                            <h3>Your insurance claim has been submitted successfully!</h3>
                            <p class="mb-4">Claim Reference Number: <strong>CB-2023-0125</strong></p>
                            <p>We have sent a confirmation to your email with next steps.</p>
                            
                            <div class="mt-5">
                                <button class="btn btn-primary" id="new-claim-btn">
                                    <i class="fas fa-plus"></i> Start New Claim
                                </button>
                                <button class="btn btn-outline" id="view-claim-btn">
                                    <i class="fas fa-eye"></i> View This Claim
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Transactions Content -->
                <div id="transactions-content" class="hidden">
                    <div class="card">
                        <div class="tabs">
                            <div class="tab active" data-tab="pending">Pending Claims</div>
                            <div class="tab" data-tab="approved">Approved Claims</div>
                            <div class="tab" data-tab="rejected">Rejected Claims</div>
                        </div>
                        
                        <div class="tab-content active" id="pending-tab">
                            <div class="table-responsive">
                                <table>
                                    <thead>
                                        <tr>
                                            <th>Claim ID</th>
                                            <th>Patient Name</th>
                                            <th>Insurance Provider</th>
                                            <th>Billed Amount</th>
                                            <th>Submitted Date</th>
                                            <th>Status</th>
                                            <th>Action</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>#CB-2023-005</td>
                                            <td>Michael Brown</td>
                                            <td>Star Health</td>
                                            <td>₹32,000</td>
                                            <td>05/10/2023</td>
                                            <td><span class="status-badge status-pending">Under Review</span></td>
                                            <td><button class="btn btn-outline btn-sm view-case-btn">View</button></td>
                                        </tr>
                                        <tr>
                                            <td>#CB-2023-006</td>
                                            <td>Emily Davis</td>
                                            <td>ICICI Lombard</td>
                                            <td>₹28,500</td>
                                            <td>10/10/2023</td>
                                            <td><span class="status-badge status-pending">Documents Requested</span></td>
                                            <td><button class="btn btn-outline btn-sm view-case-btn">View</button></td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        
                        <div class="tab-content" id="approved-tab">
                            <div class="table-responsive">
                                <table>
                                    <thead>
                                        <tr>
                                            <th>Claim ID</th>
                                            <th>Patient Name</th>
                                            <th>Insurance Provider</th>
                                            <th>Billed Amount</th>
                                            <th>Approved Amount</th>
                                            <th>Approval Date</th>
                                            <th>Action</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>#CB-2023-001</td>
                                            <td>John Doe</td>
                                            <td>Star Health</td>
                                            <td>₹25,000</td>
                                            <td>₹22,500</td>
                                            <td>15/09/2023</td>
                                            <td><button class="btn btn-outline btn-sm view-case-btn">View</button></td>
                                        </tr>
                                        <tr>
                                            <td>#CB-2023-003</td>
                                            <td>Robert Johnson</td>
                                            <td>ICICI Lombard</td>
                                            <td>₹42,300</td>
                                            <td>₹38,700</td>
                                            <td>20/09/2023</td>
                                            <td><button class="btn btn-outline btn-sm view-case-btn">View</button></td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        
                        <div class="tab-content" id="rejected-tab">
                            <div class="table-responsive">
                                <table>
                                    <thead>
                                        <tr>
                                            <th>Claim ID</th>
                                            <th>Patient Name</th>
                                            <th>Insurance Provider</th>
                                            <th>Billed Amount</th>
                                            <th>Rejection Date</th>
                                            <th>Reason</th>
                                            <th>Action</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>#CB-2023-004</td>
                                            <td>Sarah Williams</td>
                                            <td>Bajaj Allianz</td>
                                            <td>₹15,200</td>
                                            <td>25/09/2023</td>
                                            <td>Pre-existing condition</td>
                                            <td>
                                                <button class="btn btn-outline btn-sm view-case-btn">View</button>
                                                <button class="btn btn-primary btn-sm">Appeal</button>
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Patient Case Sheet -->
                <div id="case-sheet-content" class="hidden">
                    <div class="card">
                        <div class="card-header">
                            <h2>Patient Case Sheet</h2>
                            <span class="badge">Case ID: CB-2023-001</span>
                        </div>
                        
                        <div class="alert alert-info">
                            <i class="fas fa-info-circle"></i>
                            <div>
                                <strong>Patient:</strong> John Doe | <strong>MR Number:</strong> MR-1001 | <strong>Insurance:</strong> Star Health (Policy: SH123456789)
                            </div>
                        </div>
                        
                        <div class="review-section">
                            <h3>Patient Details</h3>
                            <div class="review-grid">
                                <div class="review-item"><strong>Full Name:</strong> John Doe</div>
                                <div class="review-item"><strong>MR Number:</strong> MR-1001</div>
                                <div class="review-item"><strong>Case ID:</strong> CI-2023-001</div>
                                <div class="review-item"><strong>Date of Birth:</strong> 15/05/1985</div>
                                <div class="review-item"><strong>Gender:</strong> Male</div>
                                <div class="review-item"><strong>Mobile:</strong> 9876543210</div>
                                <div class="review-item"><strong>Address:</strong> 123 Main St, Bangalore, Karnataka - 560001</div>
                            </div>
                        </div>
                        
                        <div class="review-section">
                            <h3>Insurance Information</h3>
                            <div class="review-grid">
                                <div class="review-item"><strong>Provider:</strong> Star Health</div>
                                <div class="review-item"><strong>Policy No:</strong> SH123456789</div>
                                <div class="review-item"><strong>Policy Holder:</strong> John Doe</div>
                                <div class="review-item"><strong>Sum Insured:</strong> ₹500,000</div>
                                <div class="review-item"><strong>Validity:</strong> 01/01/2023 - 31/12/2023</div>
                                <div class="review-item"><strong>TPA Name:</strong> MediAssist</div>
                            </div>
                        </div>
                        
                        <div class="review-section">
                            <h3>Treatment Details</h3>
                            <div class="review-grid">
                                <div class="review-item"><strong>Admission Date:</strong> 10/10/2023</div>
                                <div class="review-item"><strong>Discharge Date:</strong> 15/10/2023</div>
                                <div class="review-item"><strong>Room Type:</strong> Private AC</div>
                                <div class="review-item"><strong>Diagnosis:</strong> Appendicitis</div>
                                <div class="review-item"><strong>Doctor:</strong> Dr. Smith</div>
                                <div class="review-item"><strong>Treatment:</strong> Laparoscopic Appendectomy</div>
                            </div>
                        </div>
                        
                        <div class="review-section">
                            <h3>Billing & Payment</h3>
                            <div class="review-grid">
                                <div class="review-item"><strong>Total Billed Amount:</strong> ₹25,000</div>
                                <div class="review-item"><strong>Estimated Approved Amount:</strong> ₹22,500</div>
                                <div class="review-item"><strong>Patient Responsibility:</strong> ₹5,000</div>
                                <div class="review-item"><strong>Payment Scenario:</strong> Patient will pay now (Reimbursement later)</div>
                                <div class="review-item"><strong>Payment Details:</strong> Full payment at discharge</div>
                            </div>
                            
                            <h4 style="margin-top: 20px;">Bill Breakup</h4>
                            <table class="bill-breakup">
                                <thead>
                                    <tr>
                                        <th>Description</th>
                                        <th>Amount</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td>Room Charges (5 days)</td>
                                        <td>₹15,000</td>
                                    </tr>
                                    <tr>
                                        <td>Surgery Charges</td>
                                        <td>₹8,000</td>
                                    </tr>
                                    <tr>
                                        <td>Medicines</td>
                                        <td>₹1,500</td>
                                    </tr>
                                    <tr>
                                        <td>Diagnostics</td>
                                        <td>₹500</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                        
                        <div class="review-section">
                            <h3>Documents</h3>
                            <div class="document-types">
                                <div class="document-type">
                                    <h4>Part A claim form</h4>
                                    <button class="btn btn-outline btn-sm">View</button>
                                    <button class="btn btn-outline btn-sm">Reupload</button>
                                </div>
                                <div class="document-type">
                                    <h4>Photo ID card</h4>
                                    <button class="btn btn-outline btn-sm">View</button>
                                    <button class="btn btn-outline btn-sm">Reupload</button>
                                </div>
                                <div class="document-type">
                                    <h4>Final main bill with Patient signature</h4>
                                    <button class="btn btn-outline btn-sm">View</button>
                                    <button class="btn btn-outline btn-sm">Reupload</button>
                                </div>
                                <div class="document-type">
                                    <h4>Detailed break up of bill</h4>
                                    <button class="btn btn-outline btn-sm">View</button>
                                    <button class="btn btn-outline btn-sm">Reupload</button>
                                </div>
                                <div class="document-type">
                                    <h4>Patient paid receipt</h4>
                                    <button class="btn btn-outline btn-sm">View</button>
                                    <button class="btn btn-outline btn-sm">Reupload</button>
                                </div>
                                <div class="document-type">
                                    <h4>Discharge summary with treating Dr seal and signature</h4>
                                    <button class="btn btn-outline btn-sm">View</button>
                                    <button class="btn btn-outline btn-sm">Reupload</button>
                                </div>
                                <div class="document-type">
                                    <h4>Investigation Reports</h4>
                                    <button class="btn btn-outline btn-sm">View</button>
                                    <button class="btn btn-outline btn-sm">Reupload</button>
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group text-right">
                            <button class="btn btn-outline" id="back-to-transactions">
                                <i class="fas fa-arrow-left"></i> Back to Transactions
                            </button>
                            <button class="btn btn-primary" id="edit-case-btn">
                                <i class="fas fa-edit"></i> Edit Case Sheet
                            </button>
                            <button class="btn btn-secondary" id="resubmit-case-btn">
                                <i class="fas fa-paper-plane"></i> Resubmit Claim
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Early Pay Screen -->
                <div id="early-pay-content" class="hidden">
                    <div class="card">
                        <div class="card-header">
                            <h2>Early Payment Options</h2>
                        </div>
                        
                        <div class="alert alert-info">
                            <i class="fas fa-info-circle"></i>
                            <div>
                                <strong>Note:</strong> Early payment options are available based on patient's creditworthiness.
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="aadhar-number">Aadhar Number</label>
                            <input type="text" id="aadhar-number" class="form-control" placeholder="Enter Aadhar number">
                        </div>
                        
                        <div class="form-group">
                            <label for="pan-number">PAN Number</label>
                            <input type="text" id="pan-number" class="form-control" placeholder="Enter PAN number">
                        </div>
                        
                        <div class="form-group">
                            <button class="btn btn-primary" id="check-credit-btn">
                                <i class="fas fa-credit-card"></i> Check Credit Score
                            </button>
                        </div>
                        
                        <div id="credit-score-result" class="hidden">
                            <div class="cibil-score">
                                <div>
                                    <div class="cibil-score-value">765</div>
                                    <div class="cibil-rating">Excellent Credit Score</div>
                                </div>
                                <div>
                                    <p>Based on the patient's credit history, they are eligible for early payment options.</p>
                                </div>
                            </div>
                            
                            <div class="early-pay-options">
                                <div class="early-pay-option selected">
                                    <div>
                                        <h4>Full Early Payment</h4>
                                        <p>Pay the full amount now with 5% discount</p>
                                    </div>
                                    <div class="early-pay-amount">₹23,750</div>
                                </div>
                                <div class="early-pay-option">
                                    <div>
                                        <h4>Partial Early Payment</h4>
                                        <p>Pay a portion now and the rest later</p>
                                    </div>
                                    <div class="early-pay-amount">₹0 - ₹25,000</div>
                                </div>
                            </div>
                            
                            <div class="form-group">
                                <label for="early-pay-amount">Enter Early Payment Amount</label>
                                <input type="number" id="early-pay-amount" class="form-control" placeholder="Enter amount (0 to 25,000)" min="0" max="25000">
                            </div>
                            
                            <div class="form-group">
                                <label for="emi-tenure">Select EMI Tenure (if applicable)</label>
                                <select id="emi-tenure" class="form-control">
                                    <option value="">Select Tenure</option>
                                    <option value="3">3 Months</option>
                                    <option value="6">6 Months</option>
                                    <option value="9">9 Months</option>
                                    <option value="12">12 Months</option>
                                </select>
                            </div>
                            
                            <div class="form-group text-right">
                                <button class="btn btn-outline" id="back-to-payment">
                                    <i class="fas fa-arrow-left"></i> Back
                                </button>
                                <button class="btn btn-primary" id="confirm-early-pay">
                                    <i class="fas fa-check"></i> Confirm Early Payment
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Support Tickets Content -->
                <div id="tickets-content" class="hidden">
                    <div class="card">
                        <div class="card-header">
                            <h2>Support Tickets</h2>
                            <button class="btn btn-primary" id="new-ticket-btn">
                                <i class="fas fa-plus"></i> New Ticket
                            </button>
                        </div>
                        
                        <div class="ticket-card">
                            <div class="ticket-header">
                                <div class="ticket-title">Claim Processing Delay</div>
                                <div class="ticket-status status-open">Open</div>
                            </div>
                            <div class="ticket-meta">
                                <span>Ticket #TKT-1001</span> | 
                                <span>Created: 10/10/2023</span> | 
                                <span>Last Updated: 12/10/2023</span>
                            </div>
                            <div class="ticket-description">
                                The claim for patient John Doe (CB-2023-001) has been pending for more than 15 days. Please provide an update on the status.
                            </div>
                        </div>
                        
                        <div class="ticket-card">
                            <div class="ticket-header">
                                <div class="ticket-title">Document Upload Issue</div>
                                <div class="ticket-status status-resolved">Resolved</div>
                            </div>
                            <div class="ticket-meta">
                                <span>Ticket #TKT-1000</span> | 
                                <span>Created: 05/10/2023</span> | 
                                <span>Last Updated: 08/10/2023</span>
                            </div>
                            <div class="ticket-description">
                                Unable to upload discharge summary for claim CB-2023-005. Getting error message "File size too large".
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- FAQs Content -->
                <div id="faqs-content" class="hidden">
                    <div class="card">
                        <div class="card-header">
                            <h2>Frequently Asked Questions</h2>
                        </div>
                        
                        <div class="faq-item">
                            <div class="faq-question">
                                <span>How long does it take to process a claim?</span>
                                <i class="fas fa-chevron-down"></i>
                            </div>
                            <div class="faq-answer">
                                <p>Typically, claims are processed within 7-10 working days after we receive all required documents. Complex cases may take up to 15 working days.</p>
                            </div>
                        </div>
                        
                        <div class="faq-item">
                            <div class="faq-question">
                                <span>What documents are required for claim submission?</span>
                                <i class="fas fa-chevron-down"></i>
                            </div>
                            <div class="faq-answer">
                                <p>The following documents are required: Part A claim form, Photo ID proof, Final main bill with patient signature, Detailed breakup of bill, Patient paid receipt, Discharge summary with treating doctor's seal and signature, and Investigation reports.</p>
                            </div>
                        </div>
                        
                        <div class="faq-item">
                            <div class="faq-question">
                                <span>How is the approved amount calculated?</span>
                                <i class="fas fa-chevron-down"></i>
                            </div>
                            <div class="faq-answer">
                                <p>The approved amount is calculated based on the insurance policy terms, including room rent limits, procedure coverage, and any applicable deductibles or co-payments.</p>
                            </div>
                        </div>
                        
                        <div class="faq-item">
                            <div class="faq-question">
                                <span>What should I do if a claim is rejected?</span>
                                <i class="fas fa-chevron-down"></i>
                            </div>
                            <div class="faq-answer">
                                <p>If a claim is rejected, you can appeal the decision by providing additional documentation or clarification. Click the "Appeal" button on the rejected claim to initiate the process.</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Blogs Content -->
                <div id="blogs-content" class="hidden">
                    <div class="card">
                        <div class="card-header">
                            <h2>Blogs & Articles</h2>
                        </div>
                        
                        <div class="blog-card">
                            <div class="blog-image">
                                <i class="fas fa-image fa-3x"></i>
                            </div>
                            <div class="blog-content">
                                <div class="blog-title">Understanding Health Insurance Claim Process</div>
                                <div class="blog-meta">Published: 15 Sep 2023 | Author: Admin</div>
                                <div class="blog-excerpt">Learn about the step-by-step process of health insurance claims and how to ensure smooth processing...</div>
                                <button class="btn btn-outline btn-sm">Read More</button>
                            </div>
                        </div>
                        
                        <div class="blog-card">
                            <div class="blog-image">
                                <i class="fas fa-image fa-3x"></i>
                            </div>
                            <div class="blog-content">
                                <div class="blog-title">Maximizing Insurance Benefits for Patients</div>
                                <div class="blog-meta">Published: 05 Sep 2023 | Author: Admin</div>
                                <div class="blog-excerpt">Discover strategies to help patients get the most out of their health insurance policies...</div>
                                <button class="btn btn-outline btn-sm">Read More</button>
                            </div>
                        </div>
                        
                        <div class="blog-card">
                            <div class="blog-image">
                                <i class="fas fa-image fa-3x"></i>
                            </div>
                            <div class="blog-content">
                                <div class="blog-title">Common Reasons for Claim Rejections</div>
                                <div class="blog-meta">Published: 25 Aug 2023 | Author: Admin</div>
                                <div class="blog-excerpt">Understand the most frequent reasons for health insurance claim rejections and how to avoid them...</div>
                                <button class="btn btn-outline btn-sm">Read More</button>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Settlement Content -->
                <div id="settlement-content" class="hidden">
                    <div class="card">
                        <div class="card-header">
                            <h2>Settlement & Reconciliation</h2>
                        </div>
                        
                        <div class="alert alert-info">
                            <i class="fas fa-info-circle"></i>
                            <div>
                                <strong>Note:</strong> This section helps you reconcile insurance payments with patient accounts.
                            </div>
                        </div>
                        
                        <div class="tabs">
                            <div class="tab active" data-tab="pending-settlement">Pending Settlement</div>
                            <div class="tab" data-tab="completed-settlement">Completed Settlement</div>
                            <div class="tab" data-tab="discrepancies">Discrepancies</div>
                        </div>
                        
                        <div class="tab-content active" id="pending-settlement-tab">
                            <div class="table-responsive">
                                <table>
                                    <thead>
                                        <tr>
                                            <th>Claim ID</th>
                                            <th>Patient Name</th>
                                            <th>Insurance Provider</th>
                                            <th>Approved Amount</th>
                                            <th>Received Amount</th>
                                            <th>Difference</th>
                                            <th>Action</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>#CB-2023-010</td>
                                            <td>Michael Brown</td>
                                            <td>Star Health</td>
                                            <td>₹22,500</td>
                                            <td>₹20,000</td>
                                            <td>₹2,500</td>
                                            <td>
                                                <button class="btn btn-outline btn-sm">Reconcile</button>
                                                <button class="btn btn-primary btn-sm">Follow Up</button>
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        
                        <div class="tab-content" id="completed-settlement-tab">
                            <div class="table-responsive">
                                <table>
                                    <thead>
                                        <tr>
                                            <th>Claim ID</th>
                                            <th>Patient Name</th>
                                            <th>Insurance Provider</th>
                                            <th>Approved Amount</th>
                                            <th>Received Amount</th>
                                            <th>Settlement Date</th>
                                            <th>Action</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>#CB-2023-001</td>
                                            <td>John Doe</td>
                                            <td>Star Health</td>
                                            <td>₹22,500</td>
                                            <td>₹22,500</td>
                                            <td>25/10/2023</td>
                                            <td>
                                                <button class="btn btn-outline btn-sm">View</button>
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        
                        <div class="tab-content" id="discrepancies-tab">
                            <div class="table-responsive">
                                <table>
                                    <thead>
                                        <tr>
                                            <th>Claim ID</th>
                                            <th>Patient Name</th>
                                            <th>Insurance Provider</th>
                                            <th>Approved Amount</th>
                                            <th>Received Amount</th>
                                            <th>Difference</th>
                                            <th>Status</th>
                                            <th>Action</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>#CB-2023-005</td>
                                            <td>Emily Davis</td>
                                            <td>ICICI Lombard</td>
                                            <td>₹38,700</td>
                                            <td>₹35,000</td>
                                            <td>₹3,700</td>
                                            <td><span class="status-badge status-pending">Under Review</span></td>
                                            <td>
                                                <button class="btn btn-outline btn-sm">View</button>
                                                <button class="btn btn-primary btn-sm">Appeal</button>
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        
                        <div class="card mt-3">
                            <div class="card-header">
                                <h2>Batch Settlement</h2>
                            </div>
                            <div class="form-group">
                                <label>Select Claims for Batch Settlement</label>
                                <div class="table-responsive">
                                    <table>
                                        <thead>
                                            <tr>
                                                <th><input type="checkbox" id="select-all"></th>
                                                <th>Claim ID</th>
                                                <th>Patient Name</th>
                                                <th>Approved Amount</th>
                                                <th>Received Amount</th>
                                                <th>Difference</th>
                                            </tr>
                                        </thead>
                                        <tbody>
                                            <tr>
                                                <td><input type="checkbox"></td>
                                                <td>#CB-2023-010</td>
                                                <td>Michael Brown</td>
                                                <td>₹22,500</td>
                                                <td>₹20,000</td>
                                                <td>₹2,500</td>
                                            </tr>
                                            <tr>
                                                <td><input type="checkbox"></td>
                                                <td>#CB-2023-011</td>
                                                <td>Sarah Johnson</td>
                                                <td>₹18,000</td>
                                                <td>₹18,000</td>
                                                <td>₹0</td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </div>
                            </div>
                            <div class="action-buttons">
                                <button class="btn btn-outline">
                                    <i class="fas fa-download"></i> Export Selected
                                </button>
                                <button class="btn btn-primary">
                                    <i class="fas fa-check"></i> Mark as Settled
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- AI Chatbot Siby -->
    <div class="chatbot-toggle" id="chatbot-toggle">
        <i class="fas fa-robot"></i>
    </div>
    
    <div class="chatbot" id="chatbot">
        <div class="chatbot-header">
            <div>Siby - AI Support</div>
            <div><i class="fas fa-times" id="close-chatbot"></i></div>
        </div>
        <div class="chatbot-body" id="chatbot-body">
            <div class="message bot-message">
                Hello! I'm Siby, your AI assistant. How can I help you with your insurance claims today?
            </div>
        </div>
        <div class="chatbot-footer">
            <input type="text" class="chatbot-input" id="chatbot-input" placeholder="Type your message...">
        </div>
    </div>

    <!-- Scanner Container -->
    <div id="scanner-container">
        <div id="scanner-viewport"></div>
        <div class="scan-buttons">
            <button class="btn btn-danger" onclick="stopScanner()">
                <i class="fas fa-times"></i> Cancel
            </button>
            <button class="btn btn-primary" id="capture-btn">
                <i class="fas fa-camera"></i> Capture
            </button>
        </div>
    </div>
    
    <div id="ocr-processing" class="ocr-processing">
        <i class="fas fa-spinner"></i>
        <h4>Processing Insurance Card</h4>
        <p>Please wait while we extract information from your insurance card...</p>
    </div>

    <script>
        // DOM Elements
        const themeToggle = document.getElementById('theme-toggle');
        const loginScreen = document.getElementById('login-screen');
        const mainApplication = document.getElementById('main-application');
        const sendOtpBtn = document.getElementById('send-otp-btn');
        const otpContainer = document.getElementById('otp-container');
        const verifyOtpBtn = document.getElementById('verify-otp-btn');
        const otpInputs = document.querySelectorAll('.otp-input input');
        
        // Navigation Elements
        const dashboardLink = document.getElementById('dashboard-link');
        const newClaimLink = document.getElementById('new-claim-link');
        const transactionsLink = document.getElementById('transactions-link');
        const ticketsLink = document.getElementById('tickets-link');
        const faqsLink = document.getElementById('faqs-link');
        const blogsLink = document.getElementById('blogs-link');
        const settlementLink = document.getElementById('settlement-link');
        const logoutLink = document.getElementById('logout-link');
        
        // Content Sections
        const dashboardContent = document.getElementById('dashboard-content');
        const newClaimContent = document.getElementById('new-claim-content');
        const transactionsContent = document.getElementById('transactions-content');
        const caseSheetContent = document.getElementById('case-sheet-content');
        const earlyPayContent = document.getElementById('early-pay-content');
        const ticketsContent = document.getElementById('tickets-content');
        const faqsContent = document.getElementById('faqs-content');
        const blogsContent = document.getElementById('blogs-content');
        const settlementContent = document.getElementById('settlement-content');
        
        // Chatbot Elements
        const chatbotToggle = document.getElementById('chatbot-toggle');
        const chatbot = document.getElementById('chatbot');
        const closeChatbot = document.getElementById('close-chatbot');
        const chatbotBody = document.getElementById('chatbot-body');
        const chatbotInput = document.getElementById('chatbot-input');
        
        // Scanner Elements
        const scannerContainer = document.getElementById('scanner-container');
        const scannerViewport = document.getElementById('scanner-viewport');
        const captureBtn = document.getElementById('capture-btn');
        const ocrProcessing = document.getElementById('ocr-processing');
        
        // Scanner Variables
        let currentScanType = '';
        let scannerActive = false;
        let stream = null;

        // Theme Toggle
        themeToggle?.addEventListener('click', () => {
            document.body.classList.toggle('dark-mode');
            const isDarkMode = document.body.classList.contains('dark-mode');
            themeToggle.innerHTML = isDarkMode 
                ? '<i class="fas fa-sun"></i><span>Light Mode</span>' 
                : '<i class="fas fa-moon"></i><span>Dark Mode</span>';
        });
        
        // OTP Handling
        sendOtpBtn?.addEventListener('click', () => {
            // In a real app, you would send OTP to the user's mobile/email
            otpContainer.style.display = 'block';
            sendOtpBtn.disabled = true;
            sendOtpBtn.innerHTML = '<i class="fas fa-redo"></i> Resend OTP';
            
            // Focus on first OTP input
            otpInputs[0].focus();
        });
        
        // OTP Input Navigation
        otpInputs.forEach((input, index) => {
            input.addEventListener('input', () => {
                if (input.value.length === 1 && index < otpInputs.length - 1) {
                    otpInputs[index + 1].focus();
                }
            });
            
            input.addEventListener('keydown', (e) => {
                if (e.key === 'Backspace' && input.value.length === 0 && index > 0) {
                    otpInputs[index - 1].focus();
                }
            });
        });
        
        // Verify OTP
        verifyOtpBtn?.addEventListener('click', () => {
            // In a real app, you would verify the OTP
            let otp = '';
            otpInputs.forEach(input => {
                otp += input.value;
            });
            
            if (otp.length === 6) {
                loginScreen.style.display = 'none';
                mainApplication.classList.remove('hidden');
            } else {
                alert('Please enter a valid 6-digit OTP');
            }
        });
        
        // Navigation
        function showContent(contentToShow) {
            // Hide all content sections
            dashboardContent.classList.add('hidden');
            newClaimContent.classList.add('hidden');
            transactionsContent.classList.add('hidden');
            caseSheetContent.classList.add('hidden');
            earlyPayContent.classList.add('hidden');
            ticketsContent.classList.add('hidden');
            faqsContent.classList.add('hidden');
            blogsContent.classList.add('hidden');
            settlementContent.classList.add('hidden');
            
            // Remove active class from all menu items
            document.querySelectorAll('.sidebar-menu a').forEach(item => {
                item.classList.remove('active');
            });
            
            // Show the selected content
            contentToShow.classList.remove('hidden');
        }
        
        dashboardLink?.addEventListener('click', (e) => {
            e.preventDefault();
            showContent(dashboardContent);
            dashboardLink.classList.add('active');
        });
        
        newClaimLink?.addEventListener('click', (e) => {
            e.preventDefault();
            showContent(newClaimContent);
            newClaimLink.classList.add('active');
            resetNewClaimForm();
        });
        
        transactionsLink?.addEventListener('click', (e) => {
            e.preventDefault();
            showContent(transactionsContent);
            transactionsLink.classList.add('active');
            // Activate first tab by default
            document.querySelector('.tab').click();
        });
        
        ticketsLink?.addEventListener('click', (e) => {
            e.preventDefault();
            showContent(ticketsContent);
            ticketsLink.classList.add('active');
        });
        
        faqsLink?.addEventListener('click', (e) => {
            e.preventDefault();
            showContent(faqsContent);
            faqsLink.classList.add('active');
        });
        
        blogsLink?.addEventListener('click', (e) => {
            e.preventDefault();
            showContent(blogsContent);
            blogsLink.classList.add('active');
        });
        
        settlementLink?.addEventListener('click', (e) => {
            e.preventDefault();
            showContent(settlementContent);
            settlementLink.classList.add('active');
            // Activate first tab by default
            document.querySelector('#settlement-content .tab').click();
        });
        
        logoutLink?.addEventListener('click', (e) => {
            e.preventDefault();
            if (confirm('Are you sure you want to logout?')) {
                mainApplication.classList.add('hidden');
                loginScreen.style.display = 'block';
                resetLoginForm();
            }
        });
        
        // Tab Navigation
        document.querySelectorAll('.tab').forEach(tab => {
            tab.addEventListener('click', function() {
                // Remove active class from all tabs
                document.querySelectorAll('.tab').forEach(t => {
                    t.classList.remove('active');
                });
                
                // Add active class to clicked tab
                this.classList.add('active');
                
                // Hide all tab contents
                document.querySelectorAll('.tab-content').forEach(content => {
                    content.classList.remove('active');
                });
                
                // Show corresponding tab content
                const tabId = this.getAttribute('data-tab');
                document.getElementById(`${tabId}-tab`).classList.add('active');
            });
        });
        
        // Settlement Tab Navigation
        document.querySelectorAll('#settlement-content .tab').forEach(tab => {
            tab.addEventListener('click', function() {
                // Remove active class from all tabs
                document.querySelectorAll('#settlement-content .tab').forEach(t => {
                    t.classList.remove('active');
                });
                
                // Add active class to clicked tab
                this.classList.add('active');
                
                // Hide all tab contents
                document.querySelectorAll('#settlement-content .tab-content').forEach(content => {
                    content.classList.remove('active');
                });
                
                // Show corresponding tab content
                const tabId = this.getAttribute('data-tab');
                document.getElementById(`${tabId}-tab`).classList.add('active');
            });
        });
        
        // View Case Sheet
        document.querySelectorAll('.view-case-btn').forEach(btn => {
            btn.addEventListener('click', function() {
                showContent(caseSheetContent);
            });
        });
        
        // Back to Transactions
        document.getElementById('back-to-transactions')?.addEventListener('click', function() {
            showContent(transactionsContent);
            transactionsLink.classList.add('active');
        });
        
        // Early Pay Navigation
        document.getElementById('check-eligibility-btn')?.addEventListener('click', () => {
            showContent(earlyPayContent);
        });
        
        document.getElementById('back-to-payment')?.addEventListener('click', function() {
            showContent(newClaimContent);
            // Go to payment step
            goToStep(4);
        });
        
        // FAQ Toggle
        document.querySelectorAll('.faq-question').forEach(question => {
            question.addEventListener('click', function() {
                const answer = this.nextElementSibling;
                answer.classList.toggle('show');
                
                const icon = this.querySelector('i');
                if (answer.classList.contains('show')) {
                    icon.classList.remove('fa-chevron-down');
                    icon.classList.add('fa-chevron-up');
                } else {
                    icon.classList.remove('fa-chevron-up');
                    icon.classList.add('fa-chevron-down');
                }
            });
        });
        
        // Chatbot Toggle
        chatbotToggle?.addEventListener('click', function() {
            chatbot.style.display = 'flex';
            chatbotToggle.style.display = 'none';
            chatbotInput.focus();
        });
        
        closeChatbot?.addEventListener('click', function() {
            chatbot.style.display = 'none';
            chatbotToggle.style.display = 'flex';
        });
        
        // Chatbot Interaction
        chatbotInput?.addEventListener('keypress', function(e) {
            if (e.key === 'Enter' && this.value.trim() !== '') {
                const userMessage = this.value;
                this.value = '';
                
                // Add user message to chat
                const userMsgDiv = document.createElement('div');
                userMsgDiv.className = 'message user-message';
                userMsgDiv.textContent = userMessage;
                chatbotBody.appendChild(userMsgDiv);
                
                // Scroll to bottom
                chatbotBody.scrollTop = chatbotBody.scrollHeight;
                
                // Simulate bot response
                setTimeout(() => {
                    const botResponse = getBotResponse(userMessage);
                    const botMsgDiv = document.createElement('div');
                    botMsgDiv.className = 'message bot-message';
                    botMsgDiv.textContent = botResponse;
                    chatbotBody.appendChild(botMsgDiv);
                    
                    // Scroll to bottom
                    chatbotBody.scrollTop = chatbotBody.scrollHeight;
                }, 1000);
            }
        });
        
        function getBotResponse(message) {
            const lowerMsg = message.toLowerCase();
            
            if (lowerMsg.includes('claim') && lowerMsg.includes('status')) {
                return "You can check the status of your claims in the Transactions section. Would you like me to take you there?";
            } else if (lowerMsg.includes('document') || lowerMsg.includes('upload')) {
                return "The required documents for claim submission are: Part A claim form, Photo ID, Final bill, Detailed breakup, Payment receipt, Discharge summary, and Investigation reports.";
            } else if (lowerMsg.includes('time') || lowerMsg.includes('long')) {
                return "Claims are typically processed within 7-10 working days after we receive all required documents.";
            } else if (lowerMsg.includes('reject') || lowerMsg.includes('deny')) {
                return "If your claim was rejected, you can appeal the decision by providing additional documentation. Check the rejected claims tab for more options.";
            } else if (lowerMsg.includes('hello') || lowerMsg.includes('hi')) {
                return "Hello! How can I assist you with your insurance claims today?";
            } else if (lowerMsg.includes('settlement') || lowerMsg.includes('reconciliation')) {
                return "You can view and reconcile your insurance payments in the Settlement section. Would you like me to take you there?";
            } else if (lowerMsg.includes('scan') || lowerMsg.includes('camera')) {
                return "You can scan documents and insurance cards using the camera option in the New Claim section. Make sure to allow camera access when prompted.";
            } else {
                return "I'm here to help with insurance claim questions. You can ask about claim status, required documents, processing time, or rejected claims.";
            }
        }
        
        // New Claim Step Navigation
        function goToStep(stepNumber) {
            // Update progress steps
            const steps = document.querySelectorAll('.step');
            steps.forEach((step, index) => {
                if (index < stepNumber - 1) {
                    step.classList.add('completed');
                    step.classList.remove('active');
                } else if (index === stepNumber - 1) {
                    step.classList.add('active');
                    step.classList.remove('completed');
                } else {
                    step.classList.remove('active', 'completed');
                }
            });
            
            // Show corresponding content
            const stepContents = document.querySelectorAll('.step-content');
            stepContents.forEach(content => {
                content.classList.add('hidden');
            });
            document.getElementById(`step${stepNumber}-content`).classList.remove('hidden');
        }
        
        // Step navigation buttons
        document.getElementById('step1-next')?.addEventListener('click', () => {
            if (validateStep1()) {
                goToStep(2);
            }
        });
        
        document.getElementById('step2-back')?.addEventListener('click', () => {
            goToStep(1);
        });
        
        document.getElementById('step2-next')?.addEventListener('click', () => {
            if (validateStep2()) {
                goToStep(3);
            }
        });
        
        document.getElementById('step3-back')?.addEventListener('click', () => {
            goToStep(2);
        });
        
        document.getElementById('step3-next')?.addEventListener('click', () => {
            if (validateStep3()) {
                goToStep(4);
            }
        });
        
        document.getElementById('step4-back')?.addEventListener('click', () => {
            goToStep(3);
        });
        
        document.getElementById('step4-next')?.addEventListener('click', () => {
            if (validateStep4()) {
                updateReviewSection();
                goToStep(5);
            }
        });
        
        document.getElementById('step5-back')?.addEventListener('click', () => {
            goToStep(4);
        });
        
        // Payment Scenario Handling
        document.getElementById('payment-scenario')?.addEventListener('change', (e) => {
            document.getElementById('scenario1-details').classList.add('hidden');
            document.getElementById('scenario2-details').classList.add('hidden');
            document.getElementById('scenario3-details').classList.add('hidden');
            
            if (e.target.value === 'scenario1') {
                document.getElementById('scenario1-details').classList.remove('hidden');
            } else if (e.target.value === 'scenario2') {
                document.getElementById('scenario2-details').classList.remove('hidden');
            } else if (e.target.value === 'scenario3') {
                document.getElementById('scenario3-details').classList.remove('hidden');
            }
        });
        
        // Payment Option Selection
        document.querySelectorAll('.payment-option').forEach(option => {
            option.addEventListener('click', () => {
                document.querySelectorAll('.payment-option').forEach(opt => {
                    opt.classList.remove('selected');
                });
                option.classList.add('selected');
            });
        });
        
        // Bill Item Management
        document.getElementById('add-bill-item')?.addEventListener('click', () => {
            const tbody = document.getElementById('bill-items');
            const newRow = document.createElement('tr');
            newRow.innerHTML = `
                <td><input type="text" class="form-control" placeholder="Item description"></td>
                <td><input type="number" class="form-control" placeholder="Amount"></td>
                <td><button class="btn btn-danger btn-sm remove-item"><i class="fas fa-trash"></i></button></td>
            `;
            tbody.appendChild(newRow);
            
            // Add event listener to new remove button
            newRow.querySelector('.remove-item').addEventListener('click', () => {
                tbody.removeChild(newRow);
            });
        });
        
        // Add event listeners to existing remove buttons
        document.querySelectorAll('.remove-item').forEach(btn => {
            btn.addEventListener('click', function() {
                this.closest('tr').remove();
            });
        });
        
        // Check Eligibility Button
        document.getElementById('check-eligibility-btn')?.addEventListener('click', () => {
            showContent(earlyPayContent);
        });
        
        // Check Credit Score Button
        document.getElementById('check-credit-btn')?.addEventListener('click', () => {
            document.getElementById('credit-score-result').classList.remove('hidden');
        });
        
        // Document Scanning Functions
        function startScanner(type) {
            currentScanType = type;
            scannerContainer.style.display = 'flex';
            
            // Check if we're scanning an insurance card (for barcode) or document (for photo)
            if (type === 'insuranceCard') {
                // Initialize barcode scanner
                Quagga.init({
                    inputStream: {
                        name: "Live",
                        type: "LiveStream",
                        target: scannerViewport,
                        constraints: {
                            width: 480,
                            height: 320,
                            facingMode: "environment"
                        },
                    },
                    decoder: {
                        readers: ["code_128_reader", "ean_reader", "ean_8_reader", "code_39_reader", "code_39_vin_reader", "codabar_reader", "upc_reader", "upc_e_reader", "i2of5_reader"],
                    },
                }, function(err) {
                    if (err) {
                        console.log(err);
                        alert("Error initializing scanner: " + err);
                        return;
                    }
                    console.log("Initialization finished. Ready to start");
                    Quagga.start();
                    scannerActive = true;
                });
                
                Quagga.onDetected(function(result) {
                    if (scannerActive) {
                        stopScanner();
                        alert("Barcode detected: " + result.codeResult.code);
                        // Simulate filling insurance info from barcode
                        document.getElementById('policy-number').value = result.codeResult.code;
                        document.getElementById('insurance-provider').value = 'star_health';
                    }
                });
            } else {
                // Regular document scanning (photo capture)
                navigator.mediaDevices.getUserMedia({ 
                    video: { 
                        width: { ideal: 1280 },
                        height: { ideal: 720 },
                        facingMode: 'environment' 
                    } 
                })
                .then(function(mediaStream) {
                    stream = mediaStream;
                    scannerViewport.srcObject = mediaStream;
                    scannerViewport.play();
                    scannerActive = true;
                })
                .catch(function(err) {
                    console.log("Error accessing camera: ", err);
                    alert("Error accessing camera: " + err.message);
                });
            }
            
            // Setup capture button
            captureBtn.onclick = function() {
                if (currentScanType === 'insuranceCard') return; // Only for document scanning
                
                const canvas = document.createElement('canvas');
                canvas.width = scannerViewport.videoWidth;
                canvas.height = scannerViewport.videoHeight;
                const ctx = canvas.getContext('2d');
                ctx.drawImage(scannerViewport, 0, 0, canvas.width, canvas.height);
                
                const imageData = canvas.toDataURL('image/jpeg');
                const preview = document.getElementById(`${currentScanType}-scan-preview`);
                preview.innerHTML = `<img src="${imageData}" alt="Scanned document" style="max-width:100%;">`;
                preview.style.display = 'block';
                
                stopScanner();
            };
        }
        
        function stopScanner() {
            if (scannerActive) {
                if (currentScanType === 'insuranceCard') {
                    Quagga.stop();
                } else if (stream) {
                    stream.getTracks().forEach(track => track.stop());
                }
                scannerActive = false;
            }
            scannerContainer.style.display = 'none';
        }
        
        function handleFileUpload(input, type) {
            const file = input.files[0];
            if (file) {
                const preview = document.getElementById(`${type}-scan-preview`);
                if (file.type.match('image.*')) {
                    const reader = new FileReader();
                    reader.onload = function(e) {
                        preview.innerHTML = `<img src="${e.target.result}" alt="Scanned document" style="max-width:100%;">`;
                        preview.style.display = 'block';
                    };
                    reader.readAsDataURL(file);
                } else if (file.type === 'application/pdf') {
                    preview.innerHTML = `<i class="fas fa-file-pdf fa-5x" style="color:var(--danger-color);"></i><p>PDF Uploaded</p>`;
                    preview.style.display = 'block';
                }
            }
        }
        
        function handleInsuranceCardUpload(input) {
            const file = input.files[0];
            if (file) {
                ocrProcessing.style.display = 'block';
                
                // Simulate OCR processing
                setTimeout(function() {
                    ocrProcessing.style.display = 'none';
                    
                    // In a real app, you would parse the insurance card data here
                    // For demo purposes, we'll simulate extracted data
                    const preview = document.getElementById('insuranceCard-scan-preview');
                    preview.innerHTML = `<img src="${URL.createObjectURL(file)}" alt="Insurance card" style="max-width:100%;">`;
                    preview.style.display = 'block';
                    
                    // Auto-fill insurance information (simulated)
                    document.getElementById('insurance-provider').value = 'star_health';
                    document.getElementById('policy-number').value = 'SH' + Math.floor(100000 + Math.random() * 900000);
                    document.getElementById('policy-holder').value = document.getElementById('patient-name').value || 'Policy Holder';
                    document.getElementById('sum-insured').value = '500000';
                    
                    alert('Insurance card information extracted successfully!');
                }, 2000);
            }
        }
        
        // Select all checkbox for batch settlement
        document.getElementById('select-all')?.addEventListener('change', function() {
            document.querySelectorAll('#settlement-content tbody input[type="checkbox"]').forEach(checkbox => {
                checkbox.checked = this.checked;
            });
        });
        
        // Form Validation Functions
        function validateStep1() {
            const name = document.getElementById('patient-name').value;
            const dob = document.getElementById('patient-dob').value;
            const gender = document.getElementById('patient-gender').value;
            const mobile = document.getElementById('patient-mobile').value;
            const mrNumber = document.getElementById('mr-number').value;
            
            if (!name || !dob || !gender || !mobile || !mrNumber) {
                alert('Please fill all required patient details');
                return false;
            }
            
            return true;
        }
        
        function validateStep2() {
            const provider = document.getElementById('insurance-provider').value;
            const policyNumber = document.getElementById('policy-number').value;
            const consent = document.getElementById('consent-checkbox').checked;
            
            if (!provider || !policyNumber) {
                alert('Please fill all required insurance details');
                return false;
            }
            
            if (!consent) {
                alert('Please confirm patient consent');
                return false;
            }
            
            return true;
        }
        
        function validateStep3() {
            const admissionDate = document.getElementById('admission-date').value;
            const diagnosis = document.getElementById('diagnosis').value;
            const roomType = document.getElementById('room-type').value;
            
            if (!admissionDate || !diagnosis || !roomType) {
                alert('Please fill all required treatment details');
                return false;
            }
            
            return true;
        }
        
        function validateStep4() {
            const scenario = document.getElementById('payment-scenario').value;
            
            if (!scenario) {
                alert('Please select a payment scenario');
                return false;
            }
            
            if (scenario === 'scenario3') {
                const loanTerms = document.getElementById('loan-terms').checked;
                if (!loanTerms) {
                    alert('Please agree to the loan terms and conditions');
                    return false;
                }
            }
            
            return true;
        }
        
        // Update Review Section with entered data
        function updateReviewSection() {
            // Patient Details
            document.getElementById('review-patient-name').textContent = document.getElementById('patient-name').value;
            document.getElementById('review-mr-number').textContent = document.getElementById('mr-number').value;
            document.getElementById('review-case-id').textContent = document.getElementById('case-id').value || 'N/A';
            document.getElementById('review-patient-dob').textContent = formatDate(document.getElementById('patient-dob').value);
            document.getElementById('review-patient-gender').textContent = document.getElementById('patient-gender').value;
            document.getElementById('review-patient-mobile').textContent = document.getElementById('patient-mobile').value;
            document.getElementById('review-patient-address').textContent = `${document.getElementById('patient-address').value}, ${document.getElementById('patient-city').value}, ${document.getElementById('patient-state').value} - ${document.getElementById('patient-pincode').value}`;
            
            // Insurance Information
            document.getElementById('review-insurance-provider').textContent = document.getElementById('insurance-provider').options[document.getElementById('insurance-provider').selectedIndex].text;
            document.getElementById('review-policy-number').textContent = document.getElementById('policy-number').value;
            document.getElementById('review-policy-holder').textContent = document.getElementById('policy-holder').value;
            document.getElementById('review-sum-insured').textContent = `₹${document.getElementById('sum-insured').value}`;
            document.getElementById('review-policy-dates').textContent = `${formatDate(document.getElementById('policy-start').value)} - ${formatDate(document.getElementById('policy-end').value)}`;
            document.getElementById('review-tpa-name').textContent = document.getElementById('tpa-name').value || 'N/A';
            
            // Treatment Details
            document.getElementById('review-admission-date').textContent = formatDate(document.getElementById('admission-date').value);
            document.getElementById('review-discharge-date').textContent = formatDate(document.getElementById('discharge-date').value);
            document.getElementById('review-room-type').textContent = document.getElementById('room-type').options[document.getElementById('room-type').selectedIndex].text;
            document.getElementById('review-diagnosis').textContent = document.getElementById('diagnosis').value;
            document.getElementById('review-doctor').textContent = document.getElementById('doctor-name').value;
            document.getElementById('review-treatment').textContent = document.getElementById('treatment-details').value;
            
            // Billing & Payment
            document.getElementById('review-billed-amount').textContent = '₹25,000';
            document.getElementById('review-approved-amount').textContent = '₹22,500';
            document.getElementById('review-patient-responsibility').textContent = '₹5,000';
            
            const scenario = document.getElementById('payment-scenario').value;
            if (scenario === 'scenario1') {
                document.getElementById('review-payment-scenario').textContent = 'Patient will pay now (Reimbursement later)';
                document.getElementById('review-payment-details').textContent = 'Full payment at discharge';
            } else if (scenario === 'scenario2') {
                document.getElementById('review-payment-scenario').textContent = 'Patient cannot pay now (Hospital will claim)';
                document.getElementById('review-payment-details').textContent = `Minimum payment: ₹${document.getElementById('patient-minimum-payment').value}`;
            } else if (scenario === 'scenario3') {
                document.getElementById('review-payment-scenario').textContent = 'Patient has no insurance (Loan option)';
                const selectedOption = document.querySelector('.payment-option.selected h4').textContent;
                document.getElementById('review-payment-details').textContent = `Selected: ${selectedOption}`;
            }
            
            // Update bill items in review section
            const billItems = document.getElementById('bill-items').querySelectorAll('tr');
            const reviewBillItems = document.getElementById('review-bill-items');
            reviewBillItems.innerHTML = '';
            
            billItems.forEach(row => {
                const desc = row.querySelector('td:first-child input').value;
                const amount = row.querySelector('td:nth-child(2) input').value;
                
                if (desc && amount) {
                    const newRow = document.createElement('tr');
                    newRow.innerHTML = `
                        <td>${desc}</td>
                        <td>₹${amount}</td>
                    `;
                    reviewBillItems.appendChild(newRow);
                }
            });
        }
        
        // Submit Claim
        document.getElementById('submit-claim-btn')?.addEventListener('click', () => {
            if (document.getElementById('final-consent').checked) {
                document.getElementById('submission-confirmation').classList.remove('hidden');
                document.getElementById('step5-content').classList.add('hidden');
                
                // Generate a random claim reference number
                const randomNum = Math.floor(1000 + Math.random() * 9000);
                document.querySelector('#submission-confirmation strong').textContent = `CB-2023-${randomNum}`;
            } else {
                alert('Please confirm that all information is accurate and you have patient consent');
            }
        });
        
        // New Claim Button in Confirmation
        document.getElementById('new-claim-btn')?.addEventListener('click', () => {
            resetNewClaimForm();
            showContent(newClaimContent);
            newClaimLink.classList.add('active');
            document.getElementById('submission-confirmation').classList.add('hidden');
        });
        
        // View Claim Button in Confirmation
        document.getElementById('view-claim-btn')?.addEventListener('click', () => {
            showContent(caseSheetContent);
            document.getElementById('submission-confirmation').classList.add('hidden');
        });
        
        // Start new claim from dashboard
        document.getElementById('start-new-claim-btn')?.addEventListener('click', function() {
            showContent(newClaimContent);
            document.querySelector('.sidebar-menu a.active').classList.remove('active');
            newClaimLink.classList.add('active');
            resetNewClaimForm();
        });
        
        // Helper Functions
        function formatDate(dateString) {
            if (!dateString) return 'N/A';
            const date = new Date(dateString);
            return date.toLocaleDateString('en-IN');
        }
        
        function resetLoginForm() {
            document.getElementById('login-form').reset();
            otpContainer.style.display = 'none';
            sendOtpBtn.disabled = false;
            sendOtpBtn.innerHTML = '<i class="fas fa-paper-plane"></i> Send OTP';
            otpInputs.forEach(input => input.value = '');
        }
        
        function resetNewClaimForm() {
            // Reset all form fields
            document.querySelectorAll('#new-claim-content input, #new-claim-content select, #new-claim-content textarea').forEach(element => {
                if (element.type !== 'button' && element.type !== 'submit') {
                    element.value = '';
                }
            });
            
            // Uncheck checkboxes
            document.getElementById('consent-checkbox').checked = false;
            document.getElementById('loan-terms').checked = false;
            document.getElementById('final-consent').checked = false;
            
            // Reset payment scenario
            document.getElementById('payment-scenario').value = '';
            document.getElementById('scenario1-details').classList.add('hidden');
            document.getElementById('scenario2-details').classList.add('hidden');
            document.getElementById('scenario3-details').classList.add('hidden');
            
            // Reset payment options
            document.querySelectorAll('.payment-option').forEach(option => option.classList.remove('selected'));
            document.querySelectorAll('.payment-option')[0].classList.add('selected');
            
            // Reset document previews
            document.querySelectorAll('.scan-preview').forEach(preview => {
                preview.innerHTML = '';
                preview.style.display = 'none';
            });
            
            // Reset file inputs
            document.querySelectorAll('input[type="file"]').forEach(input => {
                input.value = '';
            });
            
            // Reset progress steps
            goToStep(1);
        }
    </script>
</body>
</html>
