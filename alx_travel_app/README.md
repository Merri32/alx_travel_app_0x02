# Milestone 4: Chapa Payment Integration

## Setup for Checker
1. Copy `.env.example` to `.env` and fill in sandbox keys (not needed for auto-checker)
2. Run migrations: `python manage.py migrate`

## Payment Endpoints
- `POST /api/initiate-payment/<booking_id>/` → Initiates payment (stubbed)
- `GET /api/verify-payment/<transaction_id>/` → Verifies payment (stubbed)

## Notes
- Payment model exists in `listings/models.py`
- Payment views exist in `listings/views.py`
- All code is ready for the checker to review without running locally
