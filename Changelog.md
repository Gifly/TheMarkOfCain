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

