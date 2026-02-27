Therapy Session Tracker (Virginia LCSW)A specialized clinical hour tracker designed for Virginia LCSW candidates to monitor Direct Client Contact, Supervision, and Ancillary hours with earthy-toned aesthetics and cloud persistence.🚀 Getting Started1. PrerequisitesNode.js (v18 or higher)A Firebase Project2. Local SetupClone this repository (once created).Install dependencies:npm install
Configure Firebase:Open src/App.jsx.Replace the firebaseConfig object with your credentials from the Firebase Console.Enable Anonymous Authentication and Cloud Firestore in your Firebase project.3. DevelopmentRun the app locally:npm run dev
🛠 FeaturesVA LCSW Tracking: Pre-set goals for 1,380 client hours, 100 supervision hours, and 3,000 total hours.Earthy Palette: Calm sage, clay, and linen UI.Approval Workflow: Recurring sessions generated from templates require manual approval before counting.Prior Hours: Adjust total balances for carry-over hours.Data Persistence: Automatic cloud syncing via Firebase Firestore.📦 How to Create Your Repository URLTo generate your own repository URL, run these commands in your project folder:Initialize Git:git init
Commit Files:git add .
git commit -m "Initial commit of Therapy Tracker"
Push to GitHub:Create a new repository on GitHub.Copy the "Remote URL" they provide.Run:git remote add origin YOUR_GITHUB_REPO_URL
git branch -M main
git push -u origin main
Once pushed, your repository will be live at https://github.com/yourusername/your-repo-name.
