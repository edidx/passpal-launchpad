# Architecture Diagram

## Purpose

This diagram explains the current PassPal stack in one glance.

## Core flow

Partner / Service Provider  
↓  
PassPal Flow  
↓  
Passpod Logic  
↓  
PassPal Receipt  
↓  
DIDX Public Trust Surface

## Infrastructure support

Cloudflare Runtime
- hosted flow
- orchestration
- API
- callbacks

Supabase System of Record
- flow records
- receipt records
- config and policy data
- audit state

## Short interpretation

PassPal handles the hosted trust runtime.
Passpod handles decision logic and orchestration.
DIDX is the readable trust surface.
Cloudflare runs the runtime layer.
Supabase stores the canonical operational state.
