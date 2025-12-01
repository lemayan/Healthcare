# Healthcare Management System

A modern healthcare patient management application built with Next.js.

## About

This application allows patients to register, book appointments with doctors, and manage their healthcare information. It includes an admin dashboard for healthcare providers to manage appointments efficiently.

## Tech Stack

- **Frontend:** Next.js, TypeScript, TailwindCSS
- **UI Components:** ShadCN UI
- **Backend:** Appwrite (Database, Authentication, Storage)
- **Notifications:** Twilio (SMS)
- **Monitoring:** Sentry

## Features

- Patient registration and profile management
- Book appointments with doctors
- Admin dashboard for appointment scheduling
- SMS notifications for confirmations
- Secure file uploads
- Responsive design

## Getting Started

### Prerequisites

- Node.js (v18+)
- npm or yarn
- Appwrite account

### Installation

1. Clone the repository:
```bash
git clone https://github.com/lemayan/Healthcare.git
cd Healthcare
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=your_project_id
API_KEY=your_api_key
DATABASE_ID=your_database_id
PATIENT_COLLECTION_ID=your_patient_collection_id
APPOINTMENT_COLLECTION_ID=your_appointment_collection_id
NEXT_PUBLIC_BUCKET_ID=your_bucket_id
NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

4. Run the development server:
```bash
npm run dev
```

5. Open http://localhost:3000 in your browser.

## Configuration

### Appwrite Setup

1. Create an account at [appwrite.io](https://appwrite.io/)
2. Create a new project
3. Set up the following collections:
   - Patients collection
   - Appointments collection
4. Create a storage bucket for file uploads
5. Copy your project credentials to the `.env.local` file

## License

MIT
