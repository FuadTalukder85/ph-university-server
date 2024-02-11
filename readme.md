### Requirement Analysis

[Link to Requirement Analysis Document](https://docs.google.com/document/d/10mkjS8boCQzW4xpsESyzwCCLJcM3hvLghyD_TeXPBx0/edit?usp=sharing)

Description: This document outlines the detailed analysis of project requirements.

---

### Entity-Relationship Diagrams

![ER DIAGRAM](./erdiagram.png)

Description: This is an updated diagram illustrates the relationships among User, Student, Admin, Faculty, Academic Semester, Academic Faculty, Academic Department , Course , Semester Registration , Offered Couse.

---

![POSTMAN COLLECTION](./postman_collection.json)

Description: This is a postman collection of all the API endpoints.Download this , and import it in your postman if you needed.

---

//

NODE_ENV= development
PORT=5000
DATABASE_URL=mongodb+srv://uni-admin:uni-admin@cluster0.az94fyn.mongodb.net/ph-uni?retryWrites=true&w=majority
BCRYPT_SALT_ROUNDS=12
DEFAULT_PASS=phuniversity!@#
JWT_ACCESS_SECRET = 091b2c529dec033b5ff4531e622ea3f93170e045222963319662b7e4a34f0cdd
JWT_REFRESH_SECRET = 41b991b21dc0a439cb45fed544992ba3fafa3f912d3c4dedebec3592d7d552fb74a86a4d69ea560bcf7bf988d173ddecaffa9815dd5a6661bcacd58c0cdb2dc5
JWT_ACCESS_EXPIRES_IN=10d
JWT_REFRESH_EXPIRES_IN=365d
RESET_PASS_UI_LINK= http://localhost:5173/auth/reset-password
CLOUDINARY_CLOUD_NAME=put_your_coudinary_cloud_name
CLOUDINARY_API_KEY=put_your_coudinary_api_key
CLOUDINARY_API_SECRET=put_your_coudinary_api_secret
SUPER_ADMIN_PASSWORD=admin12345
