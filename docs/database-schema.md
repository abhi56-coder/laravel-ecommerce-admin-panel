# Database Schema Plan

## users

- id
- name
- email
- password
- role
- created_at
- updated_at

## categories

- id
- name
- slug
- description
- status
- created_at
- updated_at

## products

- id
- category_id
- name
- slug
- description
- price
- stock_quantity
- image
- status
- created_at
- updated_at

## orders

- id
- user_id
- order_number
- total_amount
- payment_status
- order_status
- shipping_address
- created_at
- updated_at

## order_items

- id
- order_id
- product_id
- quantity
- price
- subtotal
- created_at
- updated_at

## coupons

- id
- code
- discount_type
- discount_value
- expiry_date
- status
- created_at
- updated_at

## inventory_logs

- id
- product_id
- change_type
- quantity
- note
- created_at
