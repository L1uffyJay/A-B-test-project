# Data dictionary

- `user_id`: experiment unit
- `assignment_time`: timestamp of experiment assignment
- `variant`: control/treatment, with casing inconsistencies
- `country`: country code, some missing and inconsistent values
- `customer_segment`: business segment, with nulls and casing issues
- `page_viewed`: whether the user loaded the test page
- `cta_clicks`: count of CTA clicks
- `converted`: binary conversion outcome
- `revenue_usd`: revenue from converted user; includes some negative values
- `page_load_seconds`: page performance measure; includes missing values
- `device_type`: device category, inconsistent casing
- `visitor_type`: new vs returning visitor, inconsistent casing
