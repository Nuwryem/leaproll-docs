LEAPROLL DATABASE V1

users

Stores all student accounts.

Fields:

- uid
- name
- email
- phone
- profilePhoto
- role (student)
- status (free, paid, inactive, completed)
- referralCode
- referredBy
- createdAt
- lastLogin
- currentRank
- currentStreak

---

admin_users

Stores admin and teacher accounts.

Fields:

- uid
- name
- email
- phone
- role (admin, teacher, counselor)
- createdAt

---

batches

Stores coaching batches.

Fields:

- batchId
- batchName
- category
- description
- startDate
- endDate
- isActive
- createdAt

Examples:

- 11th Science
- 12th Science
- Commerce
- JEE
- NEET

---

batch_memberships

Connects students to batches.

Fields:

- membershipId
- userId
- batchId
- joinedAt
- expiresAt
- status

---

videos

Fields:

- videoId
- batchId
- title
- description
- videoUrl
- uploadedBy
- createdAt

---

pdfs

Fields:

- pdfId
- batchId
- title
- description
- pdfUrl
- uploadedBy
- createdAt

---

assignments

Fields:

- assignmentId
- batchId
- title
- description
- dueDate
- fileUrl
- createdAt

---

dpps

Fields:

- dppId
- batchId
- title
- date
- createdAt

---

dpp_questions

Fields:

- questionId
- dppId
- question
- optionA
- optionB
- optionC
- optionD
- correctAnswer

---

tests

Fields:

- testId
- batchId
- title
- duration
- totalMarks
- createdAt

---

test_questions

Fields:

- questionId
- testId
- question
- optionA
- optionB
- optionC
- optionD
- correctAnswer

---

test_results

Fields:

- resultId
- testId
- studentId
- score
- percentage
- submittedAt

---

doubts

Fields:

- doubtId
- studentId
- batchId
- subject
- question
- imageUrl
- status
- answer
- answeredBy
- createdAt

---

announcements

Fields:

- announcementId
- batchId
- title
- message
- createdAt

---

admission_requests

Fields:

- requestId
- studentId
- batchId
- status
- createdAt

Status:

- pending
- approved
- rejected

---

activity_logs

Fields:

- logId
- studentId
- action
- createdAt

Examples:

- login
- watch_video
- open_pdf
- complete_dpp
- submit_test