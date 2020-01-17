# ef_core_sqlite_crash

This application is a sample to test EF Core Issue #14561. Run this web application and press the "Start Querying" button. It should crash after the process memory builds up a bit. The sqlite data file is stored in the local app data folder. You will need to manually run migrations to create the database.
