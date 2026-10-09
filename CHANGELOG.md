# Changelog FingerPrint

Todos los cambios notables de cada versión. La tarjeta dentro de la app muestra solo la primera línea; aquí va la historia completa.

## [1.2.8] - 2026-10-09

Nueva ventana para verificar identidad y contraseñas iguales a la versión anterior
New "Verificar identidad" window before Registro de asistencia: Huella / Contraseña switch like the main screen, clear verified and not-recognized states. The password tab only shows when someone has a password.
Employee passwords follow the store setting (FBPASSWORDLOCALENABLED) like WinForms: only ADMIN, and only where the store allows it.
Employee passwords accept ñ and accented letters, like WinForms.
Login accepts passwords made only of spaces, like WinForms.
Report password is no longer trimmed, so the protected Excel opens with exactly what was typed.

## [1.2.7] - 2026-10-05

Arreglos visuales
Registro de asistencia weekends were obscured slightly for easier reading.

## [1.2.6] - 2026-09-30

Arreglos de bugs
Fixed taskbar over in fullscreen mode on older windows server instances (maintenance)

## [1.2.5] - 2026-09-30

Arreglos de bugs
Fixed taskbar over in fullscreen mode on older windows server instances
Main clock now displays time based on db, not machine time

## [1.2.4] - 2026-09-30

QoL setup inicial
Initial import by pos.exe.config confirmation

## [1.2.3] - 2026-09-30

Cambio de setup inicial
Initial import by pos.exe.config
Hid config import behind admin/options

## [1.2.2] - 2026-09-30

Cambio visual (small)
Changed entrada/salida.. text below fingeprint circle to company alias

## [1.2.1] - 2026-09-30

Arreglos de compatibilidad
Update toast never appearing again after rejecting update
Update toast being eliminated on category change (entrada, salida...)
Removed variable weight on google sans font to improve compatibility

## [1.2.0] - 2026-09-29

Rediseño de pantalla principal y arreglos visuales
GrupoCanaima fallback icon
Color coded categories (entrada, salida...)
Registro de asistencia window increase 130% visual fix
Revamped a lot of the code
Main window full revamp
Admin pallete
company icon now has no white background

## [1.1.2] - 2026-09-28

Soporte de pantalla completa y arreglos generales
Fullscreen support (1.1.0)
Auto updating (1.1.0)
Versions / version control (1.1.0)
Open on startup (1.1.0)
Config file prevalence between updates (1.1.1)
Initial config setup modal not showing icon in taskbar (1.1.2)
"notes" file not being uploaded (1.1.2)
Registro de asistencia window increase 130% (1.1.0)
Notifications were tritone, now 1 single tone (1.1.0)
Pallete changes in admin panel (1.1.0)
App now sits on %localappdata% and can be uninstalled through settings remove menu (1.1.0)
Changed icon (1.1.0)

## [1.0.1] - 2026-09-25

Primera actualización distribuida (ver notas de la release v1.0.1 en GitHub).

## [1.0.0] - 2026-09-25

Primera versión publicada: port WPF del control de asistencia.
