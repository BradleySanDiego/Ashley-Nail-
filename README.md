# 💅 Ashley's Nails - Complete Booking System with Luxebook

Welcome to Ashley's Nails! A Hello Kitty themed nail salon website with an integrated professional booking system (Luxebook).

## ✨ What's Included

### 🏠 Main Website (`index.html`)
- Beautiful Hello Kitty pink theme
- Floating bow animations
- Services showcase
- Quick links to booking and admin
- Fully responsive design

### 📅 Booking System (`booking-system.html`)
**Advanced Customer Booking Interface:**
- Interactive calendar view
- Real-time availability checking
- Time slot selection
- Service selection with pricing
- User authentication (sign up/login)
- View personal appointments
- Booking confirmation
- Deal/promotion display

### 👑 Admin Dashboard (`admin.html`)
**Comprehensive Admin Panel:**
- Password-protected access (default: `admin123`)
- **Dashboard**: Stats overview (total bookings, revenue, clients)
- **Appointments Management**:
  - View all bookings in a table
  - Confirm appointments
  - Cancel appointments
  - Edit appointment details
  - Filter by status (pending/confirmed/cancelled)
- **Availability Management**:
  - Add custom availability dates
  - Set working hours
  - Define time slot durations (30/60/90 min)
  - Quick add weekdays or full week
  - Edit/remove availability
- **Services & Pricing**:
  - Add new services
  - Edit service details (name, duration, price)
  - Delete services
  - Manage service catalog
- **Deals & Promotions**:
  - Create percentage discounts
  - Create fixed amount discounts
  - Set special pricing
  - Add expiration dates
  - Apply deals to specific services
- **Client Management**:
  - View all registered clients
  - See booking history
  - Delete client accounts

## 🚀 Quick Start

### Deploy to Vercel

1. **Upload to GitHub**:
   - Create a new repository
   - Upload ALL files to the root directory
   
2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Deploy automatically

Your site pages:
- `your-site.vercel.app` - Main landing page
- `your-site.vercel.app/booking-system.html` - Customer booking
- `your-site.vercel.app/admin.html` - Admin dashboard

## 🔐 Admin Access

**Default Password:** `admin123`

To access admin:
1. Go to `your-site.vercel.app/admin.html`
2. Enter password: `admin123`
3. Start managing!

**Change Password:**
Open browser console (F12) and type:
```javascript
localStorage.setItem('luxebookAdminPass', 'your-new-password');
```

## 💾 Data Storage

The system uses **localStorage** for data persistence:
- **Availability**: Time slots and working hours
- **Services**: Your service catalog
- **Appointments**: All bookings
- **Users**: Customer accounts
- **Deals**: Active promotions
- **Admin Password**: Authentication

**Important**: Data is browser-specific. For multi-device access or production use, connect to a backend database.

## 📖 How to Use

### For Customers:
1. Visit `booking-system.html`
2. Sign up or log in
3. Select a date on the calendar
4. Choose available time slot
5. Pick a service
6. Confirm booking!

### For Admin - Full Workflow:

**Initial Setup:**
1. Login to admin dashboard
2. Go to "Services & Pricing"
3. Add your nail services (name, duration, price)
4. Go to "Manage Availability"
5. Set your working days and hours
6. Use "Quick Add" to set up the week

**Managing Bookings:**
1. Go to "Appointments" tab
2. View all bookings
3. Click "Confirm" to approve
4. Click "Edit" to modify details
5. Click "Cancel" to remove

**Creating Promotions:**
1. Go to "Deals & Promotions"
2. Enter deal name
3. Select service to apply to
4. Choose discount type
5. Set value and expiration
6. Create deal!

## 🎨 Customization

### Update Services
In admin dashboard → Services & Pricing → Add Service

### Change Theme Colors
Main landing page uses Hello Kitty pink theme. The booking system uses Luxebook's elegant theme. To customize:

Edit CSS variables in respective files:
```css
:root {
    --pink-primary: #FF69B4;
    --pink-light: #FFB6D9;
    /* etc */
}
```

### Modify Working Hours
Admin dashboard → Manage Availability → Set custom hours

## 📁 File Structure

```
ashleys-nails/
│
├── index.html              # Main landing page (Hello Kitty theme)
├── booking-system.html     # Customer booking (Luxebook)
├── admin.html              # Admin dashboard (Luxebook)
└── README.md              # This file
```

## 🌟 Key Features

### Customer Side:
✅ Calendar-based booking  
✅ Real-time availability  
✅ User accounts  
✅ Booking history  
✅ Deal displays  
✅ Mobile responsive  

### Admin Side:
✅ Complete appointment management  
✅ Availability scheduling  
✅ Service catalog management  
✅ Deals & promotions  
✅ Client database  
✅ Revenue tracking  
✅ Statistics dashboard  

## 🔧 Troubleshooting

### Bookings Not Saving?
- Enable browser localStorage
- Clear cache and reload
- Check browser console for errors

### Admin Can't Login?
- Default password: `admin123`
- Reset: `localStorage.clear()` then reload

### Availability Not Showing?
- Admin must set availability first
- Check dates are in the future
- Verify slots were saved

### Calendar Not Loading?
- Check internet connection (fonts load from Google)
- Disable ad blockers
- Try different browser

## 💡 Pro Tips

1. **Set Up Availability First**: Before customers can book, you need to add available dates/times
2. **Add Services**: Create your service menu in admin panel
3. **Create Deals**: Use promotions to attract customers
4. **Check Dashboard Daily**: Monitor new bookings and confirm them
5. **Use Quick Add**: Save time by using "Quick Add Weekdays" feature
6. **Export Data**: Copy booking table to spreadsheet for backup

## 📱 Mobile Features

Both customer and admin interfaces are fully mobile-responsive:
- Customers can book from phones
- Admins can manage bookings on mobile
- Touch-friendly calendar interface
- Responsive tables and forms

## 🆘 Support

### Common Questions:

**Q: How do customers sign up?**  
A: They click the booking page, then use the sign up tab in the modal.

**Q: Can I edit services after creating them?**  
A: Yes! Go to Services & Pricing → Click Edit on any service.

**Q: How do I see how much money I've made?**  
A: Dashboard tab shows total revenue calculated from confirmed bookings.

**Q: Can I block off vacation days?**  
A: Yes! Simply don't add availability for those dates.

**Q: How do deals work?**  
A: Create a deal, apply it to a service. The discounted price shows automatically to customers.

---

## 🚀 Advanced: Backend Integration

For production use, replace localStorage with a backend:
- Firebase for simple setup
- Supabase for PostgreSQL
- Custom Node.js/Express API
- Add email notifications
- SMS confirmations
- Payment processing

The current system is perfect for:
- Testing the workflow
- Small salons (single location)
- Personal use
- Learning/demo purposes

---

Made with 💖 for Ashley's Nails | Powered by Luxebook ✨

Stay cute! 🎀
