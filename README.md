<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>Sheri Shivaji | Professional Resume</title>

    <meta
        name="description"
        content="Professional resume of Sheri Shivaji, Computer Science Engineering graduate, Amazon Quality Associate, and aspiring Java Developer."
    />

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link
        href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Manrope:wght@400;500;600;700;800&display=swap"
        rel="stylesheet"
    >

    <!-- Bootstrap Icons -->
    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css"
    >

    <style>
        /* =========================================
           1. GLOBAL DESIGN SYSTEM
        ========================================= */

        :root {
            --primary: #172554;
            --primary-light: #1e3a8a;
            --accent: #2563eb;
            --accent-light: #dbeafe;

            --background: #eef2f7;
            --surface: #ffffff;
            --surface-soft: #f8fafc;

            --text-primary: #172033;
            --text-secondary: #64748b;
            --text-light: #cbd5e1;

            --border: #e2e8f0;
            --success: #0f766e;

            --sidebar-width: 285px;
            --resume-width: 1100px;

            --radius-sm: 8px;
            --radius-md: 14px;
            --radius-lg: 22px;

            --shadow:
                0 24px 70px rgba(15, 23, 42, 0.12);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: "Inter", sans-serif;
            background: var(--background);
            color: var(--text-primary);
            line-height: 1.6;
            padding: 40px 20px;
        }

        a {
            color: inherit;
            text-decoration: none;
        }

        button {
            font: inherit;
        }

        button,
        a {
            -webkit-tap-highlight-color: transparent;
        }

        button:focus-visible,
        a:focus-visible {
            outline: 3px solid #60a5fa;
            outline-offset: 3px;
        }

        ::selection {
            background: var(--accent-light);
            color: var(--primary);
        }

        /* =========================================
           2. TOP ACTION BAR
        ========================================= */

        .action-bar {
            max-width: var(--resume-width);
            margin: 0 auto 24px;

            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 16px;
            flex-wrap: wrap;
        }

        .action-label {
            display: flex;
            align-items: center;
            gap: 10px;

            color: var(--text-secondary);
            font-size: 13px;
            font-weight: 600;
        }

        .action-label i {
            font-size: 20px;
            color: var(--accent);
        }

        .action-buttons {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .btn {
            display: inline-flex;
            justify-content: center;
            align-items: center;
            gap: 9px;

            border: 1px solid var(--border);
            border-radius: 10px;

            padding: 11px 17px;

            font-size: 13px;
            font-weight: 700;

            cursor: pointer;
            transition:
                transform 0.2s ease,
                background 0.2s ease,
                box-shadow 0.2s ease;
        }

        .btn:hover {
            transform: translateY(-2px);
        }

        .btn-primary {
            background: var(--primary);
            color: white;
            border-color: var(--primary);
            box-shadow: 0 5px 15px rgba(23, 37, 84, 0.15);
        }

        .btn-primary:hover {
            background: var(--primary-light);
        }

        .btn-secondary {
            background: white;
            color: var(--text-primary);
        }

        .btn-secondary:hover {
            background: var(--surface-soft);
        }

        /* =========================================
           3. RESUME CANVAS
        ========================================= */

        .resume {
            max-width: var(--resume-width);
            margin: 0 auto;

            background: var(--surface);
            border-radius: var(--radius-lg);
            box-shadow: var(--shadow);

            overflow: hidden;

            display: grid;
            grid-template-columns: var(--sidebar-width) minmax(0, 1fr);
        }

        /* =========================================
           4. LEFT SIDEBAR
        ========================================= */

        .sidebar {
            background:
                radial-gradient(
                    circle at top left,
                    rgba(59, 130, 246, 0.22),
                    transparent 35%
                ),
                linear-gradient(
                    165deg,
                    #172554 0%,
                    #111c3c 55%,
                    #0f172a 100%
                );

            color: white;
            padding: 36px 26px;
        }

        .profile-mark {
            width: 74px;
            height: 74px;

            display: flex;
            justify-content: center;
            align-items: center;

            background: rgba(255, 255, 255, 0.09);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 20px;

            font-family: "Manrope", sans-serif;
            font-size: 29px;
            font-weight: 800;
            letter-spacing: -2px;

            margin-bottom: 23px;
        }

        .profile-mark span {
            color: #60a5fa;
        }

        .sidebar-name {
            font-family: "Manrope", sans-serif;
            font-size: 24px;
            font-weight: 800;
            line-height: 1.25;
            letter-spacing: -0.8px;
        }

        .sidebar-role {
            color: #93c5fd;
            font-size: 12px;
            font-weight: 700;
            line-height: 1.7;
            margin-top: 10px;
        }

        .sidebar-intro {
            color: #cbd5e1;
            font-size: 12px;
            line-height: 1.9;
            margin-top: 16px;
        }

        .sidebar-divider {
            height: 1px;
            background: rgba(255, 255, 255, 0.13);
            margin: 28px 0;
        }

        .sidebar-section {
            margin-bottom: 29px;
        }

        .sidebar-heading {
            display: flex;
            align-items: center;
            gap: 10px;

            color: white;

            font-size: 11px;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 1.5px;

            margin-bottom: 18px;
        }

        .sidebar-heading i {
            color: #60a5fa;
            font-size: 17px;
        }

        /* Contact Details */

        .contact-list {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .contact-item {
            display: flex;
            align-items: flex-start;
            gap: 11px;

            min-width: 0;
        }

        .contact-icon {
            width: 30px;
            height: 30px;
            flex-shrink: 0;

            display: flex;
            justify-content: center;
            align-items: center;

            background: rgba(255, 255, 255, 0.08);
            color: #93c5fd;
            border-radius: 8px;

            font-size: 14px;
        }

        .contact-content {
            min-width: 0;
        }

        .contact-label {
            color: #94a3b8;
            font-size: 10px;
            font-weight: 600;
            margin-bottom: 2px;
        }

        .contact-value {
            color: #f8fafc;
            font-size: 11px;
            line-height: 1.6;

            overflow-wrap: anywhere;
        }

        .contact-value a:hover {
            color: #93c5fd;
        }

        /* Skill Groups */

        .skill-group {
            margin-bottom: 18px;
        }

        .skill-group-title {
            color: #cbd5e1;
            font-size: 11px;
            font-weight: 700;
            margin-bottom: 9px;
        }

        .skill-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 7px;
        }

        .skill-tag {
            display: inline-flex;
            align-items: center;

            padding: 6px 9px;

            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 6px;

            color: #e2e8f0;
            font-size: 10px;
            font-weight: 600;

            transition:
                background 0.2s ease,
                border-color 0.2s ease;
        }

        .skill-tag:hover {
            background: rgba(96, 165, 250, 0.15);
            border-color: rgba(96, 165, 250, 0.4);
        }

        /* Sidebar Lists */

        .sidebar-list {
            list-style: none;

            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .sidebar-list li {
            display: flex;
            align-items: flex-start;
            gap: 9px;

            color: #cbd5e1;
            font-size: 11px;
            line-height: 1.8;
        }

        .sidebar-list i {
            color: #60a5fa;
            margin-top: 4px;
        }

        /* =========================================
           5. MAIN CONTENT
        ========================================= */

        .main-content {
            min-width: 0;
            padding: 39px 37px 32px;
        }

        .main-header {
            padding-bottom: 24px;
            border-bottom: 1px solid var(--border);
            margin-bottom: 28px;
        }

        .eyebrow {
            display: flex;
            align-items: center;
            gap: 8px;

            color: var(--accent);
            font-size: 10px;
            font-weight: 800;
            letter-spacing: 2px;
            text-transform: uppercase;

            margin-bottom: 11px;
        }

        .eyebrow::before {
            content: "";
            width: 25px;
            height: 2px;
            background: var(--accent);
            border-radius: 2px;
        }

        .main-title {
            font-family: "Manrope", sans-serif;
            font-size: clamp(27px, 3vw, 38px);
            font-weight: 800;
            line-height: 1.2;
            letter-spacing: -1.5px;

            color: var(--primary);
        }

        .main-title span {
            color: var(--accent);
        }

        .main-subtitle {
            margin-top: 10px;
            color: var(--text-secondary);
            font-size: 13px;
            font-weight: 600;
        }

        .header-meta {
            display: flex;
            flex-wrap: wrap;
            gap: 9px;

            margin-top: 17px;
        }

        .meta-pill {
            display: inline-flex;
            align-items: center;
            gap: 7px;

            padding: 7px 10px;

            background: var(--surface-soft);
            border: 1px solid var(--border);
            border-radius: 7px;

            color: #475569;
            font-size: 10px;
            font-weight: 600;
        }

        .meta-pill i {
            color: var(--accent);
            font-size: 13px;
        }

        /* =========================================
           6. REUSABLE SECTION COMPONENTS
        ========================================= */

        .resume-section {
            margin-bottom: 31px;
            scroll-margin-top: 20px;
        }

        .section-heading {
            display: flex;
            align-items: center;
            gap: 12px;

            margin-bottom: 20px;
        }

        .section-icon {
            width: 37px;
            height: 37px;
            flex-shrink: 0;

            display: flex;
            justify-content: center;
            align-items: center;

            background: var(--accent-light);
            color: var(--accent);

            border-radius: 10px;
            font-size: 18px;
        }

        .section-title {
            font-family: "Manrope", sans-serif;
            color: var(--primary);

            font-size: 16px;
            font-weight: 800;
            letter-spacing: -0.3px;
        }

        .section-subtitle {
            color: var(--text-secondary);
            font-size: 10px;
            margin-top: 2px;
        }

        .section-rule {
            height: 1px;
            background: var(--border);
            flex: 1;
            margin-left: 5px;
        }

        /* Summary */

        .summary-card {
            background: linear-gradient(
                135deg,
                #f8fafc,
                #eff6ff
            );

            border: 1px solid #dbeafe;
            border-radius: var(--radius-md);

            padding: 19px 20px;

            position: relative;
        }

        .summary-card::before {
            content: "";
            position: absolute;

            top: 17px;
            bottom: 17px;
            left: 0;

            width: 3px;
            background: var(--accent);
            border-radius: 0 4px 4px 0;
        }

        .summary-text {
            color: #475569;
            font-size: 12px;
            line-height: 2;
        }

        /* =========================================
           7. EXPERIENCE TIMELINE
        ========================================= */

        .timeline {
            position: relative;
            padding-left: 23px;
        }

        .timeline::before {
            content: "";

            position: absolute;
            left: 5px;
            top: 8px;
            bottom: 10px;

            width: 1px;
            background: #cbd5e1;
        }

        .timeline-item {
            position: relative;
            margin-bottom: 25px;
        }

        .timeline-item:last-child {
            margin-bottom: 0;
        }

        .timeline-dot {
            position: absolute;
            left: -23px;
            top: 5px;

            width: 11px;
            height: 11px;

            border-radius: 50%;
            background: var(--accent);
            border: 3px solid #dbeafe;

            box-sizing: content-box;
        }

        .entry-top {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 12px;
        }

        .entry-title {
            color: var(--primary);
            font-size: 13px;
            font-weight: 800;
            line-height: 1.6;
        }

        .entry-company {
            color: var(--accent);
            font-size: 11px;
            font-weight: 700;
            margin-top: 3px;
        }

        .entry-date {
            flex-shrink: 0;

            padding: 5px 8px;

            background: #f1f5f9;
            border-radius: 6px;

            color: #64748b;
            font-size: 9px;
            font-weight: 700;
            white-space: nowrap;
        }

        .entry-location {
            display: flex;
            align-items: center;
            gap: 6px;

            color: var(--text-secondary);
            font-size: 10px;
            margin-top: 7px;
        }

        .entry-description {
            color: #475569;
            font-size: 11px;
            line-height: 1.9;
            margin-top: 12px;
        }

        .entry-list {
            list-style: none;
            margin-top: 11px;

            display: flex;
            flex-direction: column;
            gap: 8px;
        }

        .entry-list li {
            display: flex;
            align-items: flex-start;
            gap: 9px;

            color: #475569;
            font-size: 11px;
            line-height: 1.8;
        }

        .entry-list i {
            color: var(--accent);
            margin-top: 4px;
            font-size: 12px;
            flex-shrink: 0;
        }

        /* =========================================
           8. PROJECT CARDS
        ========================================= */

        .project-grid {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 13px;
        }

        .project-card {
            min-width: 0;

            padding: 17px;

            background: white;
            border: 1px solid var(--border);
            border-radius: var(--radius-md);

            display: flex;
            flex-direction: column;

            transition:
                transform 0.2s ease,
                box-shadow 0.2s ease,
                border-color 0.2s ease;
        }

        .project-card:hover {
            transform: translateY(-3px);
            border-color: #bfdbfe;
            box-shadow: 0 12px 28px rgba(15, 23, 42, 0.07);
        }

        .project-card-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 10px;

            margin-bottom: 12px;
        }

        .project-symbol {
            width: 35px;
            height: 35px;
            flex-shrink: 0;

            display: flex;
            justify-content: center;
            align-items: center;

            background: #eff6ff;
            color: var(--accent);
            border-radius: 9px;

            font-size: 17px;
        }

        .project-status {
            display: inline-flex;
            align-items: center;
            gap: 5px;

            color: var(--success);
            background: #f0fdfa;

            padding: 5px 7px;
            border-radius: 5px;

            font-size: 8px;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.4px;
        }

        .project-status i {
            font-size: 9px;
        }

        .project-name {
            color: var(--primary);
            font-size: 12px;
            font-weight: 800;
            line-height: 1.6;
        }

        .project-description {
            color: var(--text-secondary);
            font-size: 10px;
            line-height: 1.9;
            margin-top: 8px;

            flex-grow: 1;
        }

        .project-features {
            margin-top: 11px;
            padding-left: 15px;

            color: #475569;
            font-size: 10px;
            line-height: 1.9;
        }

        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;

            margin-top: 14px;
        }

        .tech-chip {
            background: #f1f5f9;
            border: 1px solid #e2e8f0;

            color: #475569;

            padding: 4px 6px;
            border-radius: 5px;

            font-size: 8px;
            font-weight: 700;
        }

        .project-links {
            display: flex;
            gap: 13px;
            flex-wrap: wrap;

            margin-top: 14px;
            padding-top: 12px;

            border-top: 1px solid #f1f5f9;
        }

        .project-link {
            display: inline-flex;
            align-items: center;
            gap: 6px;

            color: var(--accent);
            font-size: 10px;
            font-weight: 800;
        }

        .project-link:hover {
            color: var(--primary);
        }

        /* =========================================
           9. EDUCATION CARDS
        ========================================= */

        .education-list {
            display: flex;
            flex-direction: column;
            gap: 13px;
        }

        .education-card {
            display: flex;
            align-items: flex-start;
            gap: 13px;

            padding: 15px;

            border: 1px solid var(--border);
            border-radius: 11px;

            background: #ffffff;
        }

        .education-icon {
            width: 37px;
            height: 37px;
            flex-shrink: 0;

            display: flex;
            align-items: center;
            justify-content: center;

            background: #f1f5f9;
            color: var(--primary);

            border-radius: 9px;
            font-size: 17px;
        }

        .education-details {
            min-width: 0;
            flex: 1;
        }

        .education-degree {
            color: var(--primary);
            font-size: 12px;
            font-weight: 800;
            line-height: 1.7;
        }

        .education-institution {
            color: #64748b;
            font-size: 10px;
            line-height: 1.8;
            margin-top: 3px;
        }

        .education-meta {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;

            margin-top: 8px;
        }

        .education-meta span {
            color: #475569;
            font-size: 9px;
            font-weight: 700;

            background: #f8fafc;
            border: 1px solid var(--border);

            padding: 4px 7px;
            border-radius: 5px;
        }

        /* =========================================
           10. ADDITIONAL INFORMATION
        ========================================= */

        .info-grid {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 12px;
        }

        .info-card {
            border: 1px solid var(--border);
            border-radius: 11px;
            padding: 14px;

            background: var(--surface-soft);
        }

        .info-card-heading {
            display: flex;
            align-items: center;
            gap: 8px;

            color: var(--primary);
            font-size: 11px;
            font-weight: 800;

            margin-bottom: 8px;
        }

        .info-card-heading i {
            color: var(--accent);
            font-size: 15px;
        }

        .info-card p {
            color: var(--text-secondary);
            font-size: 10px;
            line-height: 1.9;
        }

        /* =========================================
           11. FOOTER
        ========================================= */

        .resume-footer {
            margin-top: 28px;
            padding-top: 17px;

            border-top: 1px solid var(--border);

            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 12px;
        }

        .footer-text {
            color: #94a3b8;
            font-size: 9px;
            line-height: 1.7;
        }

        .footer-mark {
            color: var(--primary);
            font-family: "Manrope", sans-serif;
            font-size: 10px;
            font-weight: 800;
            white-space: nowrap;
        }

        .footer-mark span {
            color: var(--accent);
        }

        /* =========================================
           12. RESPONSIVE DESIGN
        ========================================= */

        @media (max-width: 850px) {
            body {
                padding: 22px 12px;
            }

            .resume {
                grid-template-columns: 235px minmax(0, 1fr);
            }

            .sidebar {
                padding: 30px 19px;
            }

            .main-content {
                padding: 30px 23px;
            }

            .project-grid {
                grid-template-columns: 1fr;
            }

            .entry-top {
                flex-wrap: wrap;
            }
        }

        @media (max-width: 620px) {
            body {
                padding: 12px 8px;
            }

            .action-bar {
                padding: 0 4px;
                margin-bottom: 15px;
            }

            .action-label {
                font-size: 11px;
            }

            .action-buttons {
                width: 100%;
            }

            .action-buttons .btn {
                flex: 1;
                padding: 11px 8px;
                font-size: 11px;
            }

            .resume {
                grid-template-columns: 1fr;
                border-radius: 15px;
            }

            .sidebar {
                padding: 28px 23px;
            }

            .sidebar-profile {
                display: grid;
                grid-template-columns: 75px minmax(0, 1fr);
                gap: 16px;
                align-items: center;
            }

            .profile-mark {
                margin-bottom: 0;
            }

            .sidebar-name {
                font-size: 22px;
            }

            .sidebar-role {
                margin-top: 5px;
            }

            .sidebar-intro {
                margin-top: 17px;
            }

            .sidebar-divider {
                margin: 23px 0;
            }

            .sidebar-section {
                margin-bottom: 25px;
            }

            .main-content {
                padding: 27px 20px;
            }

            .main-title {
                font-size: 30px;
            }

            .project-grid {
                grid-template-columns: 1fr;
            }

            .info-grid {
                grid-template-columns: 1fr;
            }

            .entry-top {
                flex-direction: column;
                gap: 7px;
            }

            .entry-date {
                align-self: flex-start;
            }

            .resume-footer {
                flex-direction: column;
                align-items: flex-start;
            }
        }

        /* =========================================
           13. PRINT / SAVE AS PDF
        ========================================= */

        @page {
            size: A4;
            margin: 0;
        }

        @media print {
            html,
            body {
                width: 210mm;
                margin: 0;
                padding: 0;
                background: white !important;
            }

            body {
                -webkit-print-color-adjust: exact !important;
                print-color-adjust: exact !important;
            }

            .action-bar {
                display: none !important;
            }

            .resume {
                width: 210mm;
                max-width: none;
                margin: 0;

                border-radius: 0;
                box-shadow: none;

                grid-template-columns: 62mm minmax(0, 1fr);
                overflow: visible;
            }

            .sidebar {
                padding: 10mm 6mm;
                background: #172554 !important;
                color: white !important;
            }

            .main-content {
                padding: 10mm 8mm 8mm;
            }

            .profile-mark,
            .contact-icon,
            .section-icon,
            .project-symbol,
            .education-icon {
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }

            .project-card,
            .education-card,
            .summary-card,
            .info-card,
            .timeline-item {
                break-inside: avoid;
                page-break-inside: avoid;
            }

            .resume-section {
                break-inside: auto;
                page-break-inside: auto;
            }

            .project-card:hover {
                transform: none;
                box-shadow: none;
            }

            a {
                text-decoration: none;
            }

            .project-link {
                color: #1d4ed8 !important;
            }

            .main-title {
                font-size: 27px;
            }

            .sidebar-name {
                font-size: 21px;
            }

            .summary-text,
            .entry-description,
            .entry-list li {
                font-size: 10px;
            }

            .project-description,
            .project-features {
                font-size: 9px;
            }

            .project-grid {
                gap: 8px;
            }

            .project-card {
                padding: 11px;
            }

            .resume-footer {
                margin-top: 18px;
            }
        }
    </style>
</head>

<body>

    <!-- =========================================
         TOP ACTION BAR
    ========================================== -->

    <div class="action-bar">
        <div class="action-label">
            <i class="bi bi-file-earmark-person"></i>
            <span>Professional Resume Builder</span>
        </div>

        <div class="action-buttons">
            <button class="btn btn-secondary" onclick="window.print()">
                <i class="bi bi-printer"></i>
                Print Resume
            </button>

            <button class="btn btn-primary" onclick="window.print()">
                <i class="bi bi-file-earmark-pdf"></i>
                Save as PDF
            </button>
        </div>
    </div>


    <!-- =========================================
         MAIN RESUME
    ========================================== -->

    <article class="resume" id="resume">

        <!-- =====================================
             LEFT SIDEBAR
        ====================================== -->

        <aside class="sidebar">

            <div class="sidebar-profile">

                <div class="profile-mark">
                    S<span>V</span>
                </div>

                <div>
                    <h1 class="sidebar-name">
                        Sheri Shivaji
                    </h1>

                    <p class="sidebar-role">
                        JAVA DEVELOPER<br>
                        SOFTWARE ENGINEER
                    </p>
                </div>

            </div>

            <p class="sidebar-intro">
                Computer Science Engineering graduate with an
                interest in Java development, web technologies,
                database-driven applications, and software quality.
            </p>

            <div class="sidebar-divider"></div>


            <!-- CONTACT -->

            <section class="sidebar-section">

                <h2 class="sidebar-heading">
                    <i class="bi bi-person-lines-fill"></i>
                    Contact
                </h2>

                <div class="contact-list">

                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="bi bi-envelope"></i>
                        </div>

                        <div class="contact-content">
                            <p class="contact-label">Email</p>

                            <p class="contact-value">
                                <a href="mailto:shivajisheri@gmail.com">
                                    shivajisheri@gmail.com
                                </a>
                            </p>
                        </div>
                    </div>


                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="bi bi-telephone"></i>
                        </div>

                        <div class="contact-content">
                            <p class="contact-label">Phone</p>

                            <p class="contact-value">
                                +91 9849483963
                            </p>
                        </div>
                    </div>


                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="bi bi-geo-alt"></i>
                        </div>

                        <div class="contact-content">
                            <p class="contact-label">Location</p>

                            <p class="contact-value">
                                Hyderabad, India
                            </p>
                        </div>
                    </div>


                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="bi bi-linkedin"></i>
                        </div>

                        <div class="contact-content">
                            <p class="contact-label">LinkedIn</p>

                            <p class="contact-value">
                                <a
                                    href="https://www.linkedin.com/in/sherishivaji2774/"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                >
                                    linkedin.com/in/sherishivaji2774
                                </a>
                            </p>
                        </div>
                    </div>


                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="bi bi-github"></i>
                        </div>

                        <div class="contact-content">
                            <p class="contact-label">GitHub</p>

                            <p class="contact-value">
                                <a
                                    href="https://github.com/SHERISHIVAJI"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                >
                                    github.com/SHERISHIVAJI
                                </a>
                            </p>
                        </div>
                    </div>


                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="bi bi-globe"></i>
                        </div>

                        <div class="contact-content">
                            <p class="contact-label">Portfolio</p>

                            <p class="contact-value">
                                <a
                                    href="https://my-portfolio-xi-nine-tkaly4qyzx.vercel.app/"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                >
                                    View Portfolio
                                </a>
                            </p>
                        </div>
                    </div>

                </div>

            </section>


            <div class="sidebar-divider"></div>


            <!-- TECHNICAL SKILLS -->

            <section class="sidebar-section">

                <h2 class="sidebar-heading">
                    <i class="bi bi-code-slash"></i>
                    Technical Skills
                </h2>


                <div class="skill-group">

                    <h3 class="skill-group-title">
                        Programming
                    </h3>

                    <div class="skill-tags">
                        <span class="skill-tag">Java</span>
                        <span class="skill-tag">JavaScript</span>
                        <span class="skill-tag">Python</span>
                        <span class="skill-tag">C++</span>
                        <span class="skill-tag">C</span>
                    </div>

                </div>


                <div class="skill-group">

                    <h3 class="skill-group-title">
                        Java Technologies
                    </h3>

                    <div class="skill-tags">
                        <span class="skill-tag">Core Java</span>
                        <span class="skill-tag">OOP</span>
                        <span class="skill-tag">Collections</span>
                        <span class="skill-tag">JDBC</span>
                        <span class="skill-tag">Servlets</span>
                        <span class="skill-tag">JSP</span>
                        <span class="skill-tag">REST APIs</span>
                    </div>

                </div>


                <div class="skill-group">

                    <h3 class="skill-group-title">
                        Web Development
                    </h3>

                    <div class="skill-tags">
                        <span class="skill-tag">HTML5</span>
                        <span class="skill-tag">CSS3</span>
                        <span class="skill-tag">React</span>
                        <span class="skill-tag">DOM</span>
                        <span class="skill-tag">Web APIs</span>
                    </div>

                </div>


                <div class="skill-group">

                    <h3 class="skill-group-title">
                        Database
                    </h3>

                    <div class="skill-tags">
                        <span class="skill-tag">SQL</span>
                        <span class="skill-tag">MySQL</span>
                        <span class="skill-tag">PostgreSQL</span>
                        <span class="skill-tag">DBMS</span>
                        <span class="skill-tag">Supabase</span>
                    </div>

                </div>


                <div class="skill-group">

                    <h3 class="skill-group-title">
                        Tools & Concepts
                    </h3>

                    <div class="skill-tags">
                        <span class="skill-tag">Git</span>
                        <span class="skill-tag">GitHub</span>
                        <span class="skill-tag">VS Code</span>
                        <span class="skill-tag">IntelliJ IDEA</span>
                        <span class="skill-tag">CRUD</span>
                        <span class="skill-tag">RBAC</span>
                        <span class="skill-tag">DSA</span>
                    </div>

                </div>

            </section>


            <div class="sidebar-divider"></div>


            <!-- LANGUAGES -->

            <section class="sidebar-section">

                <h2 class="sidebar-heading">
                    <i class="bi bi-translate"></i>
                    Languages
                </h2>

                <ul class="sidebar-list">
                    <li>
                        <i class="bi bi-check-circle-fill"></i>
                        <span>English</span>
                    </li>

                    <li>
                        <i class="bi bi-check-circle-fill"></i>
                        <span>Telugu</span>
                    </li>

                    <li>
                        <i class="bi bi-check-circle-fill"></i>
                        <span>Hindi</span>
                    </li>

                    <li>
                        <i class="bi bi-check-circle-fill"></i>
                        <span>Kannada</span>
                    </li>
                </ul>

            </section>


            <div class="sidebar-divider"></div>


            <!-- CAREER FOCUS -->

            <section class="sidebar-section">

                <h2 class="sidebar-heading">
                    <i class="bi bi-bullseye"></i>
                    Career Focus
                </h2>

                <ul class="sidebar-list">
                    <li>
                        <i class="bi bi-arrow-right-circle"></i>
                        <span>Java Development</span>
                    </li>

                    <li>
                        <i class="bi bi-arrow-right-circle"></i>
                        <span>Spring Boot</span>
                    </li>

                    <li>
                        <i class="bi bi-arrow-right-circle"></i>
                        <span>REST API Development</span>
                    </li>

                    <li>
                        <i class="bi bi-arrow-right-circle"></i>
                        <span>Full-Stack Development</span>
                    </li>
                </ul>

            </section>

        </aside>


        <!-- =====================================
             RIGHT MAIN CONTENT
        ====================================== -->

        <main class="main-content">


            <!-- HEADER -->

            <header class="main-header">

                <p class="eyebrow">
                    Professional Profile
                </p>

                <h2 class="main-title">
                    Sheri <span>Shivaji</span>
                </h2>

                <p class="main-subtitle">
                    Java Developer | Software Engineer | Full-Stack Developer
                </p>

                <div class="header-meta">

                    <span class="meta-pill">
                        <i class="bi bi-geo-alt"></i>
                        Hyderabad, India
                    </span>

                    <span class="meta-pill">
                        <i class="bi bi-mortarboard"></i>
                        B.Tech CSE
                    </span>

                    <span class="meta-pill">
                        <i class="bi bi-briefcase"></i>
                        Amazon Quality Associate
                    </span>

                </div>

            </header>


            <!-- =================================
                 PROFESSIONAL SUMMARY
            ================================== -->

            <section class="resume-section" id="summary">

                <div class="section-heading">

                    <div class="section-icon">
                        <i class="bi bi-person-badge"></i>
                    </div>

                    <div>
                        <h2 class="section-title">
                            Professional Summary
                        </h2>

                        <p class="section-subtitle">
                            Background, capabilities and career direction
                        </p>
                    </div>

                    <div class="section-rule"></div>

                </div>


                <div class="summary-card">

                    <p class="summary-text">
                        Computer Science Engineering graduate with a
                        foundation in Core Java, object-oriented programming,
                        SQL, database management, and web development.
                        Experienced in building academic and personal
                        projects involving Java, JSP, Servlets, MySQL,
                        JavaScript, React, and Supabase. Currently working
                        as a Quality Associate at Amazon in the Last Mile
                        Analytics & Quality organization, developing
                        professional experience in a structured work
                        environment. Seeking opportunities to grow as a
                        Java Developer or Software Engineer and contribute
                        to reliable, maintainable software solutions.
                    </p>

                </div>

            </section>


            <!-- =================================
                 PROFESSIONAL EXPERIENCE
            ================================== -->

            <section class="resume-section" id="experience">

                <div class="section-heading">

                    <div class="section-icon">
                        <i class="bi bi-building"></i>
                    </div>

                    <div>
                        <h2 class="section-title">
                            Professional Experience
                        </h2>

                        <p class="section-subtitle">
                            Employment and professional development
                        </p>
                    </div>

                    <div class="section-rule"></div>

                </div>


                <div class="timeline">

                    <article class="timeline-item">

                        <span class="timeline-dot"></span>

                        <div class="entry-top">

                            <div>
                                <h3 class="entry-title">
                                    Quality Associate
                                </h3>

                                <p class="entry-company">
                                    Amazon
                                </p>
                            </div>

                            <span class="entry-date">
                                Sep 2026 – Present
                            </span>

                        </div>


                        <p class="entry-location">
                            <i class="bi bi-geo-alt"></i>
                            Hyderabad, India
                        </p>


                        <p class="entry-description">
                            Working within Last Mile Analytics & Quality
                            (LMAQ), with a focus on Overall Delivery Quality.
                            Building practical experience in operational
                            quality processes, accuracy, and adherence to
                            established procedures.
                        </p>


                        <ul class="entry-list">

                            <li>
                                <i class="bi bi-check2"></i>

                                <span>
                                    Follow established procedures and
                                    quality guidelines when carrying out
                                    assigned responsibilities.
                                </span>
                            </li>

                            <li>
                                <i class="bi bi-check2"></i>

                                <span>
                                    Develop attention to detail, consistency,
                                    and process discipline in a professional
                                    work environment.
                                </span>
                            </li>

                            <li>
                                <i class="bi bi-check2"></i>

                                <span>
                                    Continue developing analytical thinking,
                                    communication, and problem-solving skills.
                                </span>
                            </li>

                        </ul>

                    </article>

                </div>

            </section>


            <!-- =================================
                 TECHNICAL PROJECTS
            ================================== -->

            <section class="resume-section" id="projects">

                <div class="section-heading">

                    <div class="section-icon">
                        <i class="bi bi-kanban"></i>
                    </div>

                    <div>
                        <h2 class="section-title">
                            Technical Projects
                        </h2>

                        <p class="section-subtitle">
                            Selected development work
                        </p>
                    </div>

                    <div class="section-rule"></div>

                </div>


                <div class="project-grid">


                    <!-- PROJECT 1 -->

                    <article class="project-card">

                        <div class="project-card-header">

                            <div class="project-symbol">
                                <i class="bi bi-diagram-3"></i>
                            </div>

                            <span class="project-status">
                                <i class="bi bi-arrow-repeat"></i>
                                In Progress
                            </span>

                        </div>


                        <h3 class="project-name">
                            SV_ORBIT
                        </h3>

                        <p class="project-description">
                            Enterprise workflow and role-based task
                            management application designed to organize
                            projects, tasks, and team collaboration.
                        </p>


                        <ul class="project-features">

                            <li>
                                Role-based application structure
                            </li>

                            <li>
                                Supabase authentication and PostgreSQL
                            </li>

                            <li>
                                Row Level Security for data access control
                            </li>

                        </ul>


                        <div class="project-tech">
                            <span class="tech-chip">React</span>
                            <span class="tech-chip">JavaScript</span>
                            <span class="tech-chip">Supabase</span>
                            <span class="tech-chip">PostgreSQL</span>
                        </div>


                        <div class="project-links">

                            <a
                                class="project-link"
                                href="https://github.com/SHERISHIVAJI"
                                target="_blank"
                                rel="noopener noreferrer"
                            >
                                <i class="bi bi-github"></i>
                                GitHub Profile
                            </a>

                        </div>

                    </article>


                    <!-- PROJECT 2 -->

                    <article class="project-card">

                        <div class="project-card-header">

                            <div class="project-symbol">
                                <i class="bi bi-shield-lock"></i>
                            </div>

                            <span class="project-status">
                                <i class="bi bi-code-slash"></i>
                                Project
                            </span>

                        </div>


                        <h3 class="project-name">
                            Navigating Privacy Conflicts in Social Media
                        </h3>

                        <p class="project-description">
                            A web application exploring privacy-related
                            concerns and user access management in
                            social media environments.
                        </p>


                        <ul class="project-features">

                            <li>
                                Java-based server-side application
                            </li>

                            <li>
                                Database connectivity using JDBC
                            </li>

                            <li>
                                User authentication and access control
                                concepts
                            </li>

                        </ul>


                        <div class="project-tech">
                            <span class="tech-chip">Java</span>
                            <span class="tech-chip">JSP</span>
                            <span class="tech-chip">Servlets</span>
                            <span class="tech-chip">MySQL</span>
                            <span class="tech-chip">JDBC</span>
                        </div>


                        <div class="project-links">

                            <a
                                class="project-link"
                                href="https://github.com/SHERISHIVAJI/Navigating_privacy_conflicts_in_social_media"
                                target="_blank"
                                rel="noopener noreferrer"
                            >
                                <i class="bi bi-github"></i>
                                View Source
                            </a>

                        </div>

                    </article>


                    <!-- PROJECT 3 -->

                    <article class="project-card">

                        <div class="project-card-header">

                            <div class="project-symbol">
                                <i class="bi bi-mic"></i>
                            </div>

                            <span class="project-status">
                                <i class="bi bi-globe"></i>
                                Web App
                            </span>

                        </div>


                        <h3 class="project-name">
                            SHERU — Virtual Assistant
                        </h3>

                        <p class="project-description">
                            Browser-based virtual assistant designed
                            around voice interaction and web technologies.
                        </p>


                        <ul class="project-features">

                            <li>
                                Speech recognition capabilities
                            </li>

                            <li>
                                Speech synthesis for spoken responses
                            </li>

                            <li>
                                Browser Web API integration
                            </li>

                        </ul>


                        <div class="project-tech">
                            <span class="tech-chip">HTML5</span>
                            <span class="tech-chip">CSS3</span>
                            <span class="tech-chip">JavaScript</span>
                            <span class="tech-chip">Web APIs</span>
                        </div>


                        <div class="project-links">

                            <a
                                class="project-link"
                                href="https://github.com/SHERISHIVAJI/Shivaji_Virtual_Assistent"
                                target="_blank"
                                rel="noopener noreferrer"
                            >
                                <i class="bi bi-github"></i>
                                Source Code
                            </a>

                            <a
                                class="project-link"
                                href="https://shivaji-virtual-assistent.vercel.app/"
                                target="_blank"
                                rel="noopener noreferrer"
                            >
                                <i class="bi bi-box-arrow-up-right"></i>
                                Live Demo
                            </a>

                        </div>

                    </article>


                    <!-- PROJECT 4 -->

                    <article class="project-card">

                        <div class="project-card-header">

                            <div class="project-symbol">
                                <i class="bi bi-graph-up-arrow"></i>
                            </div>

                            <span class="project-status">
                                <i class="bi bi-window"></i>
                                Web App
                            </span>

                        </div>


                        <h3 class="project-name">
                            SkillPulse
                        </h3>

                        <p class="project-description">
                            Frontend-focused career dashboard concept
                            designed to organize job-search activities
                            and interview preparation.
                        </p>


                        <ul class="project-features">

                            <li>
                                Job application tracking interface
                            </li>

                            <li>
                                Profile and account-related UI features
                            </li>

                            <li>
                                Interview preparation and career resources
                            </li>

                        </ul>


                        <div class="project-tech">
                            <span class="tech-chip">HTML</span>
                            <span class="tech-chip">CSS</span>
                            <span class="tech-chip">JavaScript</span>
                            <span class="tech-chip">LocalStorage</span>
                        </div>


                    </article>

                </div>

            </section>


            <!-- =================================
                 EDUCATION
            ================================== -->

            <section class="resume-section" id="education">

                <div class="section-heading">

                    <div class="section-icon">
                        <i class="bi bi-mortarboard"></i>
                    </div>

                    <div>
                        <h2 class="section-title">
                            Education
                        </h2>

                        <p class="section-subtitle">
                            Academic background
                        </p>
                    </div>

                    <div class="section-rule"></div>

                </div>


                <div class="education-list">


                    <article class="education-card">

                        <div class="education-icon">
                            <i class="bi bi-building"></i>
                        </div>

                        <div class="education-details">

                            <h3 class="education-degree">
                                Bachelor of Technology — Computer Science
                                and Engineering
                            </h3>

                            <p class="education-institution">
                                Avanthi Institute of Engineering & Technology
                            </p>

                            <div class="education-meta">
                                <span>2021 – 2025</span>
                                <span>CGPA: 8.15 / 10</span>
                            </div>

                        </div>

                    </article>

                </div>

            </section>


            <!-- =================================
                 CORE COMPETENCIES
            ================================== -->

            <section class="resume-section" id="competencies">

                <div class="section-heading">

                    <div class="section-icon">
                        <i class="bi bi-stars"></i>
                    </div>

                    <div>
                        <h2 class="section-title">
                            Core Competencies
                        </h2>

                        <p class="section-subtitle">
                            Technical and professional capabilities
                        </p>
                    </div>

                    <div class="section-rule"></div>

                </div>


                <div class="info-grid">


                    <article class="info-card">

                        <h3 class="info-card-heading">
                            <i class="bi bi-braces"></i>
                            Programming
                        </h3>

                        <p>
                            Object-oriented programming, Java fundamentals,
                            collections, problem-solving, and data
                            structures and algorithms.
                        </p>

                    </article>


                    <article class="info-card">

                        <h3 class="info-card-heading">
                            <i class="bi bi-database"></i>
                            Database Development
                        </h3>

                        <p>
                            SQL queries, relational database concepts,
                            JDBC connectivity, CRUD operations, and
                            PostgreSQL fundamentals.
                        </p>

                    </article>


                    <article class="info-card">

                        <h3 class="info-card-heading">
                            <i class="bi bi-window-stack"></i>
                            Web Development
                        </h3>

                        <p>
                            HTML, CSS, JavaScript, React fundamentals,
                            browser APIs, frontend interfaces, and
                            REST API concepts.
                        </p>

                    </article>


                    <article class="info-card">

                        <h3 class="info-card-heading">
                            <i class="bi bi-check2-square"></i>
                            Quality & Problem-Solving
                        </h3>

                        <p>
                            Attention to detail, structured procedures,
                            debugging fundamentals, validation, and
                            continuous learning.
                        </p>

                    </article>


                </div>

            </section>


            <!-- =================================
                 PROFESSIONAL DEVELOPMENT
            ================================== -->

            <section class="resume-section" id="development">

                <div class="section-heading">

                    <div class="section-icon">
                        <i class="bi bi-journal-code"></i>
                    </div>

                    <div>
                        <h2 class="section-title">
                            Professional Development
                        </h2>

                        <p class="section-subtitle">
                            Ongoing learning and technical growth
                        </p>
                    </div>

                    <div class="section-rule"></div>

                </div>


                <div class="summary-card">

                    <p class="summary-text">
                        Focused on strengthening Core Java, data structures
                        and algorithms, SQL, and backend development.
                        Exploring Spring Boot, REST API development,
                        application architecture, and the integration of
                        frontend applications with database-backed services.
                    </p>

                </div>

            </section>


            <!-- =================================
                 FOOTER
            ================================== -->

            <footer class="resume-footer">

                <p class="footer-text">
                    Resume details should reflect verified experience,
                    skills, and project implementation.
                </p>

                <p class="footer-mark">
                    SHERI <span>SHIVAJI</span>
                </p>

            </footer>


        </main>

    </article>


    <!-- =========================================
         JAVASCRIPT
    ========================================== -->

    <script>
        "use strict";

        /*
         * Resume Template Utilities
         *
         * The browser's native print dialog lets you print
         * the resume or select "Save as PDF".
         */

        document.addEventListener("DOMContentLoaded", function () {

            const resume = document.getElementById("resume");

            if (!resume) {
                console.error("Resume element was not found.");
                return;
            }

            /*
             * Update the document title before printing.
             */

            const originalTitle = document.title;

            window.addEventListener("beforeprint", function () {
                document.title = "Sheri_Shivaji_Resume";
            });

            window.addEventListener("afterprint", function () {
                document.title = originalTitle;
            });

            /*
             * Add accessible labels to project links.
             */

            const projectLinks = document.querySelectorAll(".project-link");

            projectLinks.forEach(function (link) {

                if (!link.getAttribute("aria-label")) {
                    const linkText = link.textContent.trim();
                    const projectName = link
                        .closest(".project-card")
                        ?.querySelector(".project-name")
                        ?.textContent.trim();

                    if (projectName && linkText) {
                        link.setAttribute(
                            "aria-label",
                            linkText + " for " + projectName
                        );
                    }
                }

            });

        });
    </script>

</body>
</html>
