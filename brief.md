```json
{
  "version": "1",
  "projectName": "Leave Request",
  "goal": {
    "problem": "Nhân viên xin nghỉ qua email và Excel, quản lý hay sót đơn, HR tổng hợp tay mỗi tháng.",
    "outcome": "Nhân viên gửi đơn trên web, quản lý duyệt một chạm, số ngày phép tự cập nhật."
  },
  "users": [
    {
      "persona": "Nhân viên",
      "needs": [
        "gửi đơn",
        "xem số ngày phép còn lại"
      ],
      "volume": "300 người"
    },
    {
      "persona": "Quản lý trực tiếp",
      "needs": [
        "duyệt hoặc từ chối đơn"
      ]
    },
    {
      "persona": "HR",
      "needs": [
        "báo cáo tháng"
      ]
    }
  ],
  "scope": {
    "inScope": [
      "gửi và duyệt đơn",
      "báo cáo tháng"
    ],
    "outOfScope": [
      "tính lương"
    ]
  },
  "constraints": {
    "tech": [],
    "deadline": "2026-12-15",
    "compliance": [
      "Nghị định 13/2023 về dữ liệu cá nhân"
    ],
    "hosting": "on-prem",
    "nonFunctional": []
  },
  "integrations": [],
  "successCriteria": [
    "95% đơn được xử lý trong 24 giờ",
    "HR không còn tổng hợp tay báo cáo tháng"
  ],
  "references": [],
  "approvers": {
    "prd": [
      "duy"
    ],
    "design": [
      "duy"
    ],
    "merge": [
      "duy"
    ],
    "production": [
      "duy"
    ]
  }
}
```
