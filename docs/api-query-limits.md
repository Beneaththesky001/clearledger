# API query limits

API handlers validate page and limit bounds, address shape, allowed status
values, and start/end time ranges before database or Soroban access. Invalid
values return a stable 400 response so malformed queries cannot consume RPC or
database resources.
