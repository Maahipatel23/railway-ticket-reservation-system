# Login Validation Rules & Security Policy (FR-02)

1. **Identifier**: Must be a valid 10-digit mobile number or standard email address format.
2. **Password**: Minimum length of 8 characters (NFR-03 salted hash storage).
3. **Lockout Policy**: After 5 consecutive failed login attempts, the account is temporarily locked for 15 minutes to prevent brute-force attacks.
4. **Session**: HTTPS TLS 1.2+ encrypted communication (NFR-03).
