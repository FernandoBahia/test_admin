# test_admin
comando shell pra verificar se usuario tem permissão de admin 

COMANDO:

[bool](([System.Security.Principal.WindowsIdentity]::GetCurrent()).groups -match"S-1-5-32-54-4")
