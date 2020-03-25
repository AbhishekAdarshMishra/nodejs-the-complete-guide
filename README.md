NodeJS - The Complete Guide - Udemy Course
Course Materials and Assignments

For Section 12 and above, please create a file in the same directory as app.js named 'keys.js'
and fill it with like below.

module.exports.PORT = 3000;

// Session
module.exports.SESSION_SECRET_KEY = <session_secret_key>;

// Database
module.exports.MONGODB_URI = <mongodb_database_connection_uri>;

// Email
module.exports.EMAIL_HOST = 'smtp.ethereal.email';
module.exports.EMAIL_PORT = 587;
module.exports.EMAIL_SECURE = false;
module.exports.ETHEREAL_USER = <ethereal_user>;
module.exports.ETHEREAL_PASS = <password>;

module.exports.EMAIL_SENDER = <email_address>;
