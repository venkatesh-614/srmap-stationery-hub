🖨️ SRMAP Stationery Hub

A modern, full-stack web application designed to automate and streamline the printing workflow for the SRMAP university stationery shop. This platform allows students to upload documents, customize print options, pay online, and receive a unique token for quick pickup, eliminating long queues.

🚀 Features

🎓 For Students

\*Smart Upload: Drag-and-drop interface for PDF, PNG, and Image files.

\*Automated Page Counting: Python-powered microservice accurately counts PDF pages for instant price calculation.

\*Customization: Choose from B/W, Color, Spiral Binding, Lamination, and Photo Prints.

\*Instant Pricing: Real-time cost calculation based on selected options and page count.

\*Secure Payments: Integrated Razorpay gateway for seamless UPI and card transactions.

\*Token System: Generates a unique Order Token (e.g., B-101) for easy pickup.

\*WhatsApp Notifications: "Click-to-Chat" integration for order readiness updates.

\*3D UI: Interactive 3D background animation for a modern user experience.

🛠️ For Admin (Shop Staff)

\*Live Dashboard: Real-time Kanban-style queue (New Orders -> In Progress -> Ready).

\*Instant Updates: WebSockets push new orders to the dashboard instantly without refreshing.

\*Order Management: Download student files, update status, and manage workflow.

\*Revenue Analytics: Interactive charts showing weekly, monthly, and yearly revenue trends.

\*Price Control: Update service prices instantly from the settings panel.

🛠️ Tech Stack

\*Frontend: HTML5, Tailwind CSS, JavaScript (ES6+), Three.js (3D Animation).

\*Backend: Node.js, Express.js.

\*Microservice: Python (pypdf) for PDF processing.

\*Database: lowdb (JSON-based persistent storage).

\*Real-time: ws (WebSockets).

\*Payments: Razorpay API.

\*Charts: Chart.js.

🛡️ Security Note

This repository uses Razorpay Test Keys for demonstration purposes. In a production environment, always use environment variables (.env) to store sensitive API keys and secrets.
