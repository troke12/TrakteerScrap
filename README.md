# TrakteerScrap
Ini adalah dokumentasi dari API Trakteer yang saya scrap sendiri

# Daftar Endpoint
`https://api.trakteer.id/v1/user/notifications`
### Parameter
- `id` - Ini adalah id, dapat ditemukan di DevTools
- `Authorization` - Token untuk authorization, bisa ditemukan di DevTools

Endpoint ini hanya menggunakan metode `POST`
### Hasil
```json
{
    "data": [
        {
            "object": "Notification",
            "id": "idhash",
            "type": "App\\Containers\\Tip\\Notifications\\NewTipSuccess",
            "notifiable_id": 6969,
            "data": {
                "for": "creator",
                "report_url": "reporturl",
                "order_id": "orderid",
                "ordered_at": "27/02/2021 (09:19)",
                "expired_at": "27/02/2021 (09:44)",
                "order_page": "order_page",
                "creator_name": "createor_name",
                "creator_page": "creator_page",
                "creator_image": "creator_image",
                "supporter_email": "supporter_email",
                "supporter_name": "supporter_name",
                "supporter_image": "supporter_image",
                "support_message": "support_message",
                "unit_name": "unit_name",
                "unit_icon": "unit_icon",
                "quantity": 1,
                "price": "price",
                "method": "methodpayment",
                "status": "success",
                "status_label": "Sukses",
                "gopay_qrcode": "https://help.trakteer.id/en/blog/panduan-trakteer-menggunakan-ovo",
                "action_url": "action_url"
            },
            "read_at": {
                "date": "2021-02-27 21:22:59.000000",
                "timezone_type": 3,
                "timezone": "Asia/Jakarta"
            },
            "created_at": {
                "date": "2021-02-27 21:19:40.000000",
                "timezone_type": 3,
                "timezone": "Asia/Jakarta"
            },
            "readable_created_at": "1 jam yang lalu",
            "readable_updated_at": "57 menit yang lalu"
        },
    ],
    "meta": {
        "include": [],
        "custom": [],
        "pagination": {
            "total": 82,
            "count": 6,
            "per_page": 6,
            "current_page": 1,
            "total_pages": 14,
            "links": {
                "next": "https://api.trakteer.id/v1/user/notifications?page=2"
            }
        }
    }
}
```
