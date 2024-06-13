# Changelog

Este es un archivo para documentar los cambios por cada commit para el proyecto *The Mask of Cain*.

- #### Explicaciones
    - ##### Añadido
    - ##### Modificado
    - ##### Arreglado
    - ##### Borrado
    - ##### Corregido

### v[0.0.0] 08-04-2024
##### Añadido
- initial commit
- Base Project

### v[1.0.0] 08-04-2024
#### Añadido
- `BP_Cain` character
- `ABP_Cain` animation blueprint
- `BP_TheMarkOfCain` GameMode
- `CainLocomotion1D` Blendspace
- Animation, SFX and Weapons Meshes Pack 

### v[1.0.1] 10-04-2024
#### Añadido
- `StatusComponent`
- `BP_PlayerCombat` UI

### v[1.0.2] 10-04-2024
#### Añadido
- Stamina Refresh System 
- Walk/Run mechanic 
- `IA_Run_Roll_Avoid` Input Action

### v[1.0.3] 11-04-2024
#### Añadido
- Walking Mechanic
- `IA_Walking` Input Action

### v[1.0.4] 17-04-2024
#### Añadido
- `AM_PlayerRoll` Animation Montage
- `AM_PlayerJumpBackward` Animation Montage
- `Rolling` Animation 
- `Jump_Backward` Animation Montage
#### Modificado
- `ABP_Cain` Invencibility frames
- `BP_Cain` Roll and Jump Backwards logic 
- `E_PlayerState` Roll and Jump Backwards added


### v[1.0.5] 17-04-2024
#### Modificado
- `BP_Cain` Input Buffer added

### v[1.0.6] 22-04-2024
#### Añadido
- `Hoz` Mesh/Textures  
- `AM_PlayerLightAttacks` Animation Montages
- `AM_AttackRunning` Animation Montage
- `Structure` Animations container
#### Modificado
- `SK_Manny` RightHandSocket
- `BP_Cain` Equip Weapon Logic

### v[1.0.7] 25-04-2024
#### Añadido 
- `IA_PrimaryAttack` Input Action
#### Modificado
- Enabled root motion in every animation montage
- `IMC_Default` added new Input Action
- `BP_Cain` GetCorrectAttackAnimation and CheckIfCounterExceedsAttack functions added

### v[1.0.8] 27-04-2024
#### Añadido
- `AM_EnemyHitFront/Back/Left/Right` Animation Montages
- `BP_MasterEnemy` General Enemy Blueprint for child creation
- `E_HitAngle` Enumerator for hit angles
- `I_Interactions` to comunicate dealing damage between blueprints
- `UI_HPBarEnemy` UI for enemy health bar
#### Modificado
- `ABP_Cain` Line trace logic added
- Animation Montages StartTrace and EndTrace added
- `BP_Cain` Dealing Damage Logic 
- `Status Component` Decrease Health Logic
- `Receive Damage` Interface added to `BP_MasterEnemy` and `BP_Cain`

### v[1.0.9] 30-04-2024
#### Añadido 
- Lock On Mechanic
#### Modificado
- Solved animations not running 

### v[1.1.0] 30-05-2024
#### Añadido 
- Lvl3 Blocking 


### v[1.1.1] 30-05-2024
#### Añadido 
- Cain Skeletal Mesh
- Cain Materials
- Cain Mesh
- Cain robe with physics

### v[1.1.2] 05-06-2024
#### Añadido
- Main Menu Logic

### v[1.1.3] 05-06-2024
#### Añadido
- Controls in to main menu
- UI mode in Main Menu
- Sliders for volume in Main Menu

### v[1.1.4] 05-06-2024
#### Añadido
- Pause Menu logic

### v[1.1.5] 06-06-2024
#### Añadido
- Game Save Audio Logic
- Audio Sliders working

### v[1.1.6] 06-06-2024
#### Añadido 
- New Cain Skeletal Mesh 
- New Cain Textures
- Provisional Cain Animation

### v[1.1.7] 10-06-2024
#### Añadido
- IDLE, RUN, JOG, WALK Animations 

### v[1.1.8] 10-06-2024
#### Añadido
- UI Assets for Main Menu
- Corrected anims
#### Eliminado
- FirstHardAttack animation

### v[1.1.9] 10-06-2024
#### Añadido 
- FirstHard/Light Animations with montages
#### Eliminado
- SecondHard/Light Animations

### v[1.2.0] 10-06-2024
#### Añadido
- SecondHard/Light Animation with montages
#### Eliminado
- ThirdHard/Light Animations

### v[1.2.1] 10-06-2024
#### Añadido
- ThirdHard/Light Animations
#### Elimine
- RunAttack animations

### v[1.2.2] 10-06-2024
#### Añadido
- RunAttack animation with montage

### v[1.2.3] 11-06-2024
#### Eliminado
- Run animations

### v[1.2.4] 11-06-2024
#### Añadido
- Heavy/Light/Run Attacks Corrected with root motion enabled
- UI Assets added

### v[1.2.5] 12-06-2024
#### Añadido
- Catedral 

### v[1.2.6] 12-06-2024
#### Añadido
- Video pre Main menu