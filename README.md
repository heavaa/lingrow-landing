# lingrow-landing

lingrow 사전등록(waitlist) 랜딩 페이지 — 정적 단일 페이지.

- 이메일 폼 → Supabase `waitlist` 테이블 (RLS: anon insert만, select 차단)
- anon key는 RLS로 보호되는 **공개 키**
- 호스팅: GitHub Pages
