# Athithya – A Native Heritage and Geo-Origin Product Promotion Platform

Athithya is a digital ecosystem designed to empower rural communities by connecting artisans, SHGs, NGOs, and rural hosts directly with consumers.
The platform focuses on authenticity, trust, and cultural preservation—offering verified rural products, homestays, workshops, and immersive experiences.

---

##Project Overview

Rural creators often struggle due to:
- Limited digital presence 
- Dependence on intermediaries 
- Lack of trust and verification 
- Fragmented access to cultural experiences 
- Poor visibility of NGO work 
- Erosion of native traditions 

Athithya addresses these gaps through a **unified, credibility-driven digital platform** offering:
- Verified creator profiles 
- Geo-origin product listings 
- Authentic cultural experiences 
- NGO-verified impact showcases 
- Integrated bookings and secure payments 

---

##Vision

To build a trusted digital ecosystem that:
- Connects rural artisans, SHGs, NGOs, and communities to global consumers 
- Preserves cultural heritage and traditional skills 
- Enables sustainable, fair-income opportunities 

---

##Features

###**Rural Product Marketplace**
- Listings for GI-tagged and native products 
- Creator verification and Samrudhi Score 
- Clear sourcing information and cultural storytelling 

###**Homestays & Cultural Experiences**
- Village walks, workshops, local crafts, and festivals 
- Community-verified hosts 
- Transparent booking flows and secure payments 

###**NGO Impact Dashboard**
- Verified NGO profiles 
- Project transparency and updates 
- Transparent community-driven reviews 

###**Multi-Step Verification**
- NGO → Community → Admin 
- Prevents fake listings 
- Builds trust for tourists and buyers 

###**Map-Based Discovery**
- Explore villages, creators, and experiences visually 
- Hyperlocal filtering system 

### 📱 **Platform Tech Stack**
- Flutter (Mobile + Web App) 
- Django REST Framework 
- PostgreSQL (Supabase Database) 
- Secure Payment Gateway (Stripe Integration) 
- Cloud Deployment 

---

## Architecture

```
Frontend (Flutter)
     |
     |--> API Requests
     |
Backend (Django REST Framework)
     |
     |--> Authentication
     |--> Verification Logic
     |--> Product & Experience Listings
     |--> Samrudhi Score Engine
     |
PostgreSQL (Supabase)
     |
     |--> User Data, Listings, NGOs, Orders
```

---

##Project Status

###Completed
- Market research (surveys + stakeholder interviews) 
- Feature and requirement definition 
- Architecture finalization 
- Core UI screens (Flutter) 
- Backend APIs and authentication 
- Supabase schema + verification logic 
- Stripe payment integration 
- Usability + performance testing 
- Pilot launch in selected rural region 

###In Progress
- Feedback analysis 
- UI/UX refinement 
- Bug fixes and optimization 

###Upcoming Milestones
- Multi-region launch 
- Onboarding campaigns for artisans + NGOs 
- Continuous feature improvements 

---

##Survey Insights (Voice of Customer)

Key findings from 127 respondents:
- **65%** aware of artisan platforms 
- **70%** trust verified creators 
- **45%** demand authenticity as top buying factor 
- **75%** want integrated booking + payments 
- **80%** value cultural preservation 

These insights guided the verification workflow and platform design.

---

##Differentiators

- Multi-step verification 
- Community-powered credibility (Samrudhi Score) 
- Integrated ecosystem for products + experiences + NGO impact 
- Hyperlocal map-based discovery 
- Vernacular support (Malayalam + English/Hindi) 
- Transparent and ethical platform design 

---

##Revenue Model (PLCRM)

**Performance-Linked Creator Revenue Model**
- New creators or few reviews → Lower commission 
- Highly rated creators → Standard commission 
- Encourages quality service and visibility 
- Zero cost for tourists 

Additional revenue streams:
- Commission from experiences/workshops 
- Commission from rural product sales 

---

##Stakeholders

### Direct Beneficiaries
- Artisans 
- Self-Help Groups (SHGs) 
- NGOs 
- Rural homestay hosts 
- Local experience providers

###Indirect Beneficiaries
- Rural communities 
- Tourists 
- Regional economies 

---

##Verification Workflow

```
Creator applies
      ↓
NGO validates identity + authenticity
      ↓
Local community endorses
      ↓
Admin final approval
      ↓
Listing goes live with Samrudhi Score
```

---

##Installation & Setup

### Prerequisites
- Flutter SDK 
- Python 3.10+ 
- PostgreSQL / Supabase account 
- Stripe developer account 

### Steps

1. **Clone Repository**
```
git clone https://github.com/sangeethsgit/Athithya-Village-Stay-Application
cd Athithya-Village-Stay-Application
```

2. **Setup Backend**
```
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

3. **Setup Flutter App**
```
cd app
flutter pub get
flutter run
```

4. **Configure Environment**
- Add Supabase URL & API keys 
- Add Stripe secret keys 
- Update map API keys 

---

## Testing

- Unit tests for Django backend 
- Flutter widget and flow tests 
- Pilot testing with real rural creators 
- Performance and usability tests in low-bandwidth conditions

---

##Success Metrics

- Merchant onboarding numbers 
- Adoption of verification workflow 
- User bookings and product purchases 
- Community engagement 
- Trust score improvements 
- Rural income uplift

---

##Team

- Sangeeth S 
- K R Abhinand Babu 
- Krishnanand PS 
- Joshen Paul 
- Amarnad KM 

---

##License
This project is open-source under the MIT License.

---

##Contact

```
Team Athithya
TKM College of Engineering
Kollam, Kerala
```

---

