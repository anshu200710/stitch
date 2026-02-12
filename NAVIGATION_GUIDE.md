# VyaaparSaathi - Complete Navigation Guide

## 📱 Application Overview

**VyaaparSaathi** is a business management application with the following key features:
- User authentication (Login/Signup)
- Business dashboard
- Services management
- Request/Order handling
- Payment management
- Admin controls
- Document management
- Business calculators (GST, etc.)

---

## 🗺️ GETTING STARTED

### Access the Main Navigation Hub
**Start here:** Open `index.html` in your browser
- This is the central hub with links to all pages
- Organized by functional sections
- Click any page to navigate

---

## 📊 COMPLETE PAGE MAP & FLOW

### 1️⃣ **AUTHENTICATION FLOW** (Pages 1-3)
Entry point for all users

```
index.html
    ↓
splash_screen/code.html (Loading screen)
    ↓
login_screen/code.html (User login)
    ↓
signup_screen/code.html (New registration) → login_screen → user_dashboard
```

**Page Details:**
- **Splash Screen** (`splash_screen/code.html`)
  - App loading/welcome screen
  - Shows VyaaparSaathi branding
  - Displays loading spinner
  - Navigation: → Login Screen

- **Login Screen** (`login_screen/code.html`)
  - Email & password input
  - Forgot password link
  - Sign up redirect
  - Navigation: → Dashboard, → Signup

- **Sign Up Screen** (`signup_screen/code.html`)
  - Registration form (Name, Email, Password)
  - Social login options (Google, Apple)
  - Terms & conditions checkbox
  - Navigation: → Login, ← Back

---

### 2️⃣ **USER DASHBOARD** (Pages 4-6)
Main user interface after login

```
user_dashboard/code.html (Main hub)
    ├→ user_profile_screen/code.html (Profile settings)
    ├→ user_notifications/code.html (Messages & alerts)
    └→ services_list/code.html (Browse services)
```

**Page Details:**
- **User Dashboard** (`user_dashboard/code.html`)
  - Main interface after login
  - User overview & quick actions
  - Navigation links to all features

- **User Profile** (`user_profile_screen/code.html`)
  - User information management
  - Settings & preferences

- **User Notifications** (`user_notifications/code.html`)
  - Messages and alerts
  - Notification center

---

### 3️⃣ **SERVICES MANAGEMENT** (Pages 7-9)
Browse, manage, and create services

```
services_list/code.html (Browse all services)
    ├→ offers_&_freebies/code.html (Special deals)
    └→ admin_services_list/code.html (Admin management)
```

**Page Details:**
- **Services List** (`services_list/code.html`)
  - View all available services
  - Search & filter options
  - Service details view

- **Offers & Freebies** (`offers_&_freebies/code.html`)
  - Special promotions
  - Limited time offers
  - Coupon codes

- **Admin Services List** (`admin_services_list/code.html`)
  - Manage services (Admin only)
  - Add/Edit/Delete services
  - Service configuration

---

### 4️⃣ **REQUESTS & ORDERS** (Pages 10-12)
Track and manage service requests

```
request_details/code.html (Single request view)
    ├→ request_submitted_success/code.html (Confirmation)
    └→ admin_requests_list/code.html (All requests - Admin)
        └→ admin_request_detail_view/code.html (Request details)
```

**Page Details:**
- **Request Details** (`request_details/code.html`)
  - View individual request information
  - Status tracking
  - Actions & updates

- **Request Success** (`request_submitted_success/code.html`)
  - Order confirmation screen
  - Receipt information
  - Next steps

- **Admin Requests List** (`admin_requests_list/code.html`)
  - View all user requests
  - Approve/Reject requests
  - Manage request status

- **Admin Request Detail View** (`admin_request_detail_view/code.html`)
  - Detailed request analysis
  - User information
  - Request history

---

### 5️⃣ **PAYMENTS** (Pages 13-14)
Transaction management

```
payment_history/code.html (User transaction history)
    └→ admin_payments_overview/code.html (Admin payment analytics)
```

**Page Details:**
- **Payment History** (`payment_history/code.html`)
  - User transaction records
  - Invoice view
  - Download receipts

- **Admin Payments Overview** (`admin_payments_overview/code.html`)
  - Payment analytics
  - Revenue reports
  - Commission tracking

---

### 6️⃣ **CALCULATOR TOOLS** (Pages 15-17)
Business calculation utilities

```
calculator_home/code.html (Calculator selection)
    ├→ gst_calculator_input/code.html (GST input form)
    │   └→ calculator_result/code.html (Results display)
    └→ calculator_result/code.html (Direct results)
```

**Page Details:**
- **Calculator Home** (`calculator_home/code.html`)
  - Select calculation type
  - Tool navigation hub

- **GST Calculator Input** (`gst_calculator_input/code.html`)
  - Input form for GST calculation
  - Amount entry
  - Tax rate selection

- **Calculator Result** (`calculator_result/code.html`)
  - Display calculation results
  - Breakdown of calculations
  - Export/Share options

---

### 7️⃣ **DOCUMENT MANAGEMENT** (Pages 18-19)
Handle business documents

```
my_documents_list/code.html (Document library)
    └→ upload_document_screen/code.html (Upload new documents)
```

**Page Details:**
- **My Documents** (`my_documents_list/code.html`)
  - View all uploaded documents
  - Download & preview
  - Document categories

- **Upload Document** (`upload_document_screen/code.html`)
  - Upload new documents
  - Drag & drop support
  - File type validation

---

### 8️⃣ **ADMIN PANEL** (Pages 20-23)
Administrative controls

```
admin_dashboard/code.html (Admin home)
    ├→ admin_users_list/code.html (User management)
    ├→ admin_services_list/code.html (Service management)
    ├→ admin_create_offer/code.html (Create promotions)
    └→ admin_send_notification/code.html (Send messages)
```

**Page Details:**
- **Admin Dashboard** (`admin_dashboard/code.html`)
  - Admin overview & statistics
  - Quick action buttons
  - Key metrics

- **Admin Users List** (`admin_users_list/code.html`)
  - Manage user accounts
  - View user details
  - Activate/Deactivate users

- **Admin Create Offer** (`admin_create_offer/code.html`)
  - Create promotional offers
  - Set discounts & terms
  - Schedule campaigns

- **Admin Send Notification** (`admin_send_notification/code.html`)
  - Send messages to users
  - Broadcast notifications
  - Schedule messages

---

### 9️⃣ **ADDITIONAL PAGES** (Pages 24-25)
Miscellaneous functionality

- **Edit Service Form** (`add/edit_service_form/code.html`)
  - Modify service details
  - Update pricing & descriptions

---

## 🔗 QUICK NAVIGATION FLOWS

### Common User Journey
```
1. Splash Screen (3s auto-load)
2. Login Screen (email + password)
3. User Dashboard (main interface)
4. Browse Services
5. Create Request
6. Payment
7. View Notifications
8. Manage Profile
```

### Admin Workflow
```
1. Login Screen
2. Admin Dashboard
3. Manage Users/Services/Offers
4. View Requests & Payments
5. Send Notifications
```

### Calculator Usage
```
1. User Dashboard
2. Calculator Home (tool selection)
3. GST Calculator Input (data entry)
4. Calculator Result (view results)
```

---

## 🎨 DESIGN CONSISTENCY

All pages use:
- **Color Scheme:** Primary Blue (#137fec), Light backgrounds
- **Font:** Manrope (Google Fonts)
- **Framework:** Tailwind CSS
- **Icons:** Material Icons
- **Mobile-first:** Responsive design (max-width: 448px phone view)

---

## 📋 NAVIGATION TIPS

### Each Page Has:
✅ Back to Navigation link (goes to `index.html`)
✅ Internal navigation links
✅ Contextual next/previous page buttons
✅ Mobile-friendly layout
✅ Dark mode support

### To Navigate Between Pages:
1. Use the **Back to Navigation** link to return to `index.html`
2. Use page-specific navigation buttons for related pages
3. Use the Navigation Hub to jump to any page directly

---

## 📂 FILE STRUCTURE

```
stitch/
├── index.html (← START HERE)
├── splash_screen/
│   └── code.html
├── login_screen/
│   └── code.html
├── signup_screen/
│   └── code.html
├── user_dashboard/
│   └── code.html
├── user_profile_screen/
│   └── code.html
├── user_notifications/
│   └── code.html
├── services_list/
│   └── code.html
├── offers_&_freebies/
│   └── code.html
├── admin_services_list/
│   └── code.html
├── request_details/
│   └── code.html
├── request_submitted_success/
│   └── code.html
├── admin_requests_list/
│   └── code.html
├── admin_request_detail_view/
│   └── code.html
├── payment_history/
│   └── code.html
├── admin_payments_overview/
│   └── code.html
├── calculator_home/
│   └── code.html
├── gst_calculator_input/
│   └── code.html
├── calculator_result/
│   └── code.html
├── my_documents_list/
│   └── code.html
├── upload_document_screen/
│   └── code.html
├── admin_dashboard/
│   └── code.html
├── admin_users_list/
│   └── code.html
├── admin_create_offer/
│   └── code.html
├── admin_send_notification/
│   └── code.html
├── add/
│   └── edit_service_form/
│       └── code.html
└── NAVIGATION_GUIDE.md (← This file)
```

---

## 🚀 QUICK START

1. **Open in Browser:** Navigate to `index.html` in your browser
2. **View Navigation Hub:** See all 25 pages organized by section
3. **Click Any Page:** Jump directly to that page
4. **Use Page Navigation:** Each page has back/next buttons
5. **Explore Features:** Click through the complete application flow

---

## 💡 TIPS

- **Page Links Auto-Update:** All pages now link to each other
- **Consistent Navigation:** Every page has a "Back to Navigation" link
- **Mobile Responsive:** View on phone-sized screen for best experience
- **Dark Mode Ready:** Application supports dark mode (dark: prefixed classes)
- **Modern Design:** Uses Tailwind CSS for consistent styling

---

## ✨ What's Been Connected

✅ All 25 pages are now interconnected
✅ Navigation hub created (`index.html`)
✅ Back/Next buttons on all key pages
✅ Page flow documentation completed
✅ Organized by functional sections
✅ Mobile-friendly layout maintained

**Ready to explore? Open `index.html` to start!** 🎉

---

*Last Updated: February 2026*
*VyaaparSaathi - Your Business Companion*
