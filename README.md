# checkin_system

This project is a check-in system implemented using Python and the Django framework.

## Key Features:
1. Basic CRUD operations are implemented in a RESTful API style using `rest_framework`.
2. Familiarity with `django_filters` is utilized to make query parameter code more concise.

## API:
1. `127.0.0.1/api/Hrdata`
   - Create personnel data with CRUD operations implemented in a RESTful API style.
   - Allows querying employees under specific supervisors or departments using `django_filters`.
2. `127.0.0.1/api/Checkindata`
   - Only allows querying check-in records, implemented using `ReadOnlyModelViewSet` from `rest_framework`.
   - Allows querying check-in records of specific employees using `django_filters`.
3. `127.0.0.1/api/checkin`
   - Check-in.
4. `127.0.0.1/api/SupervisorCheck`
   - Query check-in records of employees under specific supervisors on specific dates.
