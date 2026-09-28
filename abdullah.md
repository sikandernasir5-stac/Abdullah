# step 1
open window and type cmd 
after cmd open 
cd desktop
npx create-next-app@Latest myname
abdullah.nextjs
cd abdullah.nextjs
npm install@supabase/supabase.js
nom run dev
http://localhost:3000

# step 2
we browse supabase on google
then open supabse and add account
after login supabase with google account
we create our project
after project created we connect supabase with next.js folder
add file on next.js folder .env.local

# step 3
.env.local
open next.js folder and create new file .env.local
add copy link in .env.local
NEXT_PUBLIC_SUPABASE_URL=YOUR_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=YOUR_SUPABASE_PUBLISHABLE_KEY

# step 4
Supabase client file;
Create A supabase,
lib/supabase.js

CODE:
</> java script
import { createClient } from "@supabase/supabase-js";

const supabaseUrl = process.env.NEXT_PUBLIC_SUPABASE_URL;
const supabaseKey = process.env.NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY;

export const supabase = createClient(
  supabaseUrl,
  supabaseKey
);
departyment;

columns:
id          = int8 - Primary Key
name        = text
description = text
Example data:







