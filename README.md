# Python-OTP-Verification-System

This Python script provides a simple OTP verification flow via the command line.
1)	 Features & Functions
•	otp_generation(): Generates a random 6-digit OTP string.As the OTP doesn’t come in calculations work.
•	simulation_otp_to_mail(email, otp): Simulates sending the otp to email, including a 2-seconds delay. 
•	get_otp_from_user(): Prompts the user for a 6-digit OTP input, validates it, and returns the valid string.
•	otp_verification(actual_otp, entered_otp): Compares the generated and entered OTPs, returning True for a match, False otherwise.
•	run_otp_verification(max_attempts=3): The main function orchestrating the entire process:
        o	Asks for user email.
        o	Generates and "sends" OTP.
        o	Prompts for OTP entry (up to max_attempts tries).
        o	Prints success/failure messages.
        o	Returns True on successful verification, False on failure.

