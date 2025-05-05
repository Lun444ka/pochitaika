// Панель инструментов редактирования с кнопками форматирования
import React from 'react';
import { Button } from '@/components/ui/button';
import { Input } from '@/components/ui/input';
import { Bold, Italic, Underline, Heading1, Heading2, Quote, Link, Image, Video, Type, Palette } from 'lucide-react';
import { Popover, PopoverContent, PopoverTrigger } from '@/components/ui/popover';
import { Tabs, TabsContent, TabsList, TabsTrigger } from '@/components/ui/tabs';
import { Slider } from '@/components/ui/slider';
import { Select, SelectContent, SelectItem, SelectTrigger, SelectValue } from "@/components/ui/select";

// Компонент реализует функциональность форматирования текста, добавления ссылок,
// изображений (как по URL, так и с локального устройства), видео,
// изменения размера и цвета шрифта
