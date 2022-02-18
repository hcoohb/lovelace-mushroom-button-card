# Lovelace-mushroom-button-card
The intention is to build a collection of [button-card](https://github.com/custom-cards/button-card) templates to match the theme of the [mushroom-cards](https://github.com/piitaya/lovelace-mushroom) for the cards not present in lovelace-mushroom, or cards adding some features/customization.  
> Note that a key difference with the nice [UI Lovelace Minimalist](https://github.com/UI-Lovelace-Minimalist/UI/) is that you can still use the lovelace UI editor.  
> Primarily for my personnal use but sharing in case it helps someone.

## Usage

-  [button-card](https://github.com/custom-cards/button-card) must be installed for all below cards
-  Specific other requirements may be needed as specified

1. Ensure all requirements are met
2. In the `Raw configuration editor` in the Lovelace UI editor, copy the code from the `templates.yml` file at the top (adapt if you already ahve some button-card templates).
3. In the dashboard, add a `Manual card` and place the usage code provided below tweaking as necessary.

### Cards

#### 1.  🌡 Climate card

![image](https://user-images.githubusercontent.com/12975783/154590201-6b472286-c60c-4a86-b7e8-60bf63aa4a89.png)
![image](https://user-images.githubusercontent.com/12975783/154589300-45531ded-2632-4932-b203-450009b755b3.png)

<details><summary>See usage</summary>
  
> Requirements:
> - Button-card
> 
> Manual card code:
> ```yaml
> type: custom:button-card
> template: mushroom_climate
> entity: climate.main_ac
> ```
</details>
  

