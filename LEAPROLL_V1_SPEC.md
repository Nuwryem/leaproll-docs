LEAPROLL V1 SPECIFICATION

1. Project Vision

LeapRoll is a coaching management platform consisting of two separate applications:

1. LeapRoll Student App
2. LeapRoll Admin App

Students can sign up independently and use free features. After joining a coaching batch, admins can assign them to a batch and unlock premium content.

---

2. Student App

Authentication

- Signup
- Login
- Forgot Password
- Logout

Home Screen

- Welcome Message
- Streak
- Rank
- Upcoming Tests
- Pending DPP
- Announcements

Study Screen

- Videos
- PDF Bank
- Assignments
- DPPs
- Tests
- Doubts

Batches Screen

- Available Batches
- Joined Batches
- Request Admission

Profile Screen

- Student Information
- Rank
- Achievements
- Referral Code
- Settings

---

3. Admin App

Dashboard

- Total Students
- Paid Students
- Free Users
- Pending Doubts
- Quick Actions

Students

- Search Student
- View Student
- Assign Batch
- Remove Batch
- Contact Student

Batches

- Create Batch
- Edit Batch
- End Batch
- Add Students
- Remove Students

Content

- Upload Videos
- Upload PDFs
- Upload Assignments
- Upload DPPs

Tests

- Create Test
- Publish Results

Doubts

- View Doubts
- Reply To Doubts

Leads

- View Free Users
- Track Interested Students
- Contact Students

---

4. User Roles

Free User

- Access Demo Content
- View Batches
- Request Admission

Paid Student

- Access Batch Content
- Videos
- PDFs
- DPPs
- Tests
- Doubts

Admin

- Full Access

---

5. Database Collections

users

batches

batch_memberships

videos

pdfs

assignments

dpps

tests

test_results

doubts

announcements

admission_requests

activity_logs

---

6. Admission Flow

Student Downloads App

→ Sign Up

→ Free User

→ Uses Demo Content

→ Requests Admission

→ Admin Receives Request

→ Admin Assigns Batch

→ Premium Features Unlock

---

7. MVP Features

Included

- Authentication
- Batch Management
- Videos
- PDFs
- DPPs
- Tests
- Doubts
- Admission Requests

Excluded

- AI Tutor
- Parent App
- Live Classes
- Battleground
- Advanced Analytics